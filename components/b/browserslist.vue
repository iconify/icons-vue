<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/t/tz7dlcc-l.css';
import '../../css/a/ah8b_-xeq.css';
import '../../css/r/rqh9r0b_f.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":16,"height":16};
const content = `<g class="tz7dlcc-l"><path class="ah8b_-xeq"/><path class="rqh9r0b_f"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="catppuccin:browserslist" /></template>
