<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/y/y0odedbyc.css';
import '../../css/f/ffal_wb_v.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":32,"height":32};
const content = `<path class="y0odedbyc"/><path class="ffal_wb_v"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="carbon:document" /></template>
