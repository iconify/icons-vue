<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/c/ct-4h76ph.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":21,"height":21};
const content = `<path class="ct-4h76ph"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="system-uicons:arrow-top-left" /></template>
