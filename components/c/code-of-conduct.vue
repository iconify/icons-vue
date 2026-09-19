<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/g/gej5qbeik.css';
import '../../css/o/oaf-ekb5m.css';
import '../../css/q/qawp00bnx.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":16,"height":16};
const content = `<g class="gej5qbeik"><path class="oaf-ekb5m"/><path class="qawp00bnx"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="catppuccin:code-of-conduct" /></template>
