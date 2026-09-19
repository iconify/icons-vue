<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/f/ft5dv1b6b.css';
import '../../css/i/imff4s__r.css';
import '../../css/v/vzvjqggfh.css';
import '../../css/h/h8mm66bgl.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":32,"height":32};
const content = `<g class="ft5dv1b6b"><path class="imff4s__r"/><path class="vzvjqggfh"/><path class="h8mm66bgl"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="fluent-emoji-flat:chart-decreasing" /></template>
