<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/f/ft5dv1b6b.css';
import '../../css/k/k84vybbzx.css';
import '../../css/r/roow3r2cc.css';
import '../../css/l/lf34zubqx.css';
import '../../css/d/dlqac-the.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":80,"height":80};
const content = `<g class="ft5dv1b6b"><path class="k84vybbzx"/><path clip-rule="evenodd" class="roow3r2cc"/><path class="lf34zubqx"/><path clip-rule="evenodd" class="dlqac-the"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="glyphs:head-side-outline" /></template>
