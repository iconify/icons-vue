<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/z/z59r8p4po.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":21,"height":21};
const content = `<path class="z59r8p4po"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="system-uicons:code" /></template>
