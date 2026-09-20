<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/x/xmdw-9bte.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":21,"height":21};
const content = `<path class="xmdw-9bte"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="system-uicons:arrow-right" /></template>
