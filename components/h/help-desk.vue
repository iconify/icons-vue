<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/i/iegve_lwq.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":32,"height":32};
const content = `<path class="iegve_lwq"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="carbon:help-desk" /></template>
