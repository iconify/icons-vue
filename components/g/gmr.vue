<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/i/ilxgl2y6d.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":32,"height":32};
const content = `<path class="ilxgl2y6d"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="cryptocurrency:gmr" /></template>
