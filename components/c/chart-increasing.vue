<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/f/ft5dv1b6b.css';
import '../../css/s/smiwupvsw.css';
import '../../css/v/vzvjqggfh.css';
import '../../css/t/thbtttbfi.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":32,"height":32};
const content = `<g class="ft5dv1b6b"><path class="smiwupvsw"/><path class="vzvjqggfh"/><path class="thbtttbfi"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="fluent-emoji-flat:chart-increasing" /></template>
