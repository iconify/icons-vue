<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/i/i1u63nvrj.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="i1u63nvrj"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="mingcute:edge-line" /></template>
