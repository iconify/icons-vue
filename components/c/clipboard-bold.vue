<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/f/ft5dv1b6b.css';
import '../../css/l/l26hlcvna.css';
import '../../css/d/dpqbvn50y.css';
import '../../css/m/mqhfzvbma.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":80,"height":80};
const content = `<g class="ft5dv1b6b"><path clip-rule="evenodd" class="l26hlcvna"/><path class="dpqbvn50y"/><rect class="mqhfzvbma"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="glyphs:clipboard-bold" /></template>
