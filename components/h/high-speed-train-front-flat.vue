<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/b/bi12bsetm.css';
import '../../css/q/q3r7l856c.css';
import '../../css/f/frvb35qqr.css';
import '../../css/h/h0aue6b3g.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":14,"height":14};
const content = `<g clip-rule="evenodd" class="bi12bsetm"><path class="q3r7l856c"/><path class="frvb35qqr"/><path class="h0aue6b3g"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="streamline-color:high-speed-train-front-flat" /></template>
