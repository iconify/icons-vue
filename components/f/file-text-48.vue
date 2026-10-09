<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/d/dezwopb-j.css';
import '../../css/c/cxl60bbqd.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":48,"height":48};
const content = `<path class="dezwopb-j"/><path class="cxl60bbqd"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="energy-icons:file-text-48" /></template>
