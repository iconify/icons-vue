<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/f/ft5dv1b6b.css';
import '../../css/o/ogxepvf0r.css';
import '../../css/k/kszy58azx.css';
import '../../css/o/ojqphszdh.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":80,"height":80};
const content = `<g class="ft5dv1b6b"><path clip-rule="evenodd" class="ogxepvf0r"/><path class="kszy58azx"/><path clip-rule="evenodd" class="ojqphszdh"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="glyphs-poly:lightbulb-1" /></template>
