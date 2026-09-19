<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/f/ft5dv1b6b.css';
import '../../css/t/t8ij2fbdm.css';
import '../../css/q/q6_pmxs6i.css';
import '../../css/a/alq95cbaz.css';
import '../../css/c/cjb0rbclx.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":80,"height":80};
const content = `<g class="ft5dv1b6b"><path clip-rule="evenodd" class="t8ij2fbdm"/><path clip-rule="evenodd" class="q6_pmxs6i"/><path class="alq95cbaz"/><path class="cjb0rbclx"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="glyphs-poly:joker" /></template>
