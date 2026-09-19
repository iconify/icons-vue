<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/u/ulra56alq.css';
import '../../css/s/s3yqb5bmb.css';
import '../../css/q/qtquy_brk.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":16,"height":16};
const content = `<g class="ulra56alq"><path class="s3yqb5bmb"/><path class="qtquy_brk"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="catppuccin:gatsby" /></template>
