<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/f/ft5dv1b6b.css';
import '../../css/j/j65d55bdx.css';
import '../../css/e/ebk4kbb8v.css';
import '../../css/a/aamyo7pvu.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":80,"height":80};
const content = `<g class="ft5dv1b6b"><path class="j65d55bdx"/><path class="ebk4kbb8v"/><path class="aamyo7pvu"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="glyphs:arrow-line-start-bold" /></template>
