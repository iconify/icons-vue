<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/e/e7s9u4b3i.css';
import '../../css/j/jn8qy4bru.css';
import '../../css/g/g0si_9w_c.css';
import '../../css/q/qyp590b_w.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":72,"height":72};
const content = `<circle class="e7s9u4b3i"/><g class="jn8qy4bru"><path class="g0si_9w_c"/><path class="qyp590b_w"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="openmoji:head-shaking-vertically" /></template>
