<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/z/z_bz0t0lf.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":32,"height":32};
const content = `<path class="z_bz0t0lf"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="carbon:chart-bar-overlay" /></template>
