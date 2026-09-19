<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/c/cuyn6tgcc.css';
import '../../css/u/uhb779nue.css';
import '../../css/g/g9wzcsquv.css';
import '../../css/b/bcsqw5n-n.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":80,"height":80};
const content = `<g class="cuyn6tgcc"><path class="uhb779nue"/><path clip-rule="evenodd" class="g9wzcsquv"/><path class="bcsqw5n-n"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="glyphs:heart-sparkles-bold" /></template>
