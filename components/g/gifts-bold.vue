<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/f/ft5dv1b6b.css';
import '../../css/i/i174wac8g.css';
import '../../css/q/qzjjwq58s.css';
import '../../css/x/x0y4czihj.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":80,"height":80};
const content = `<g class="ft5dv1b6b"><path clip-rule="evenodd" class="i174wac8g"/><path class="qzjjwq58s"/><path class="x0y4czihj"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="glyphs:gifts-bold" /></template>
