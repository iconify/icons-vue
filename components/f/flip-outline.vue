<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/f/ft5dv1b6b.css';
import '../../css/m/m63r7jbfo.css';
import '../../css/j/j46aqcc-v.css';
import '../../css/k/kiibvmbtk.css';
import '../../css/q/q0eay4bxs.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":80,"height":80};
const content = `<g class="ft5dv1b6b"><path clip-rule="evenodd" class="m63r7jbfo"/><path class="j46aqcc-v"/><path clip-rule="evenodd" class="kiibvmbtk"/><path class="q0eay4bxs"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="glyphs:flip-outline" /></template>
