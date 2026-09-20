<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/y/y0m3r4bvh.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":21,"height":21};
const content = `<path class="y0m3r4bvh"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="system-uicons:grid-small" /></template>
