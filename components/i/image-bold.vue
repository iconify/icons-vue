<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/c/cuyn6tgcc.css';
import '../../css/r/rmanxnaqh.css';
import '../../css/h/h8v7_hsyz.css';
import '../../css/t/tktzuhbfv.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":80,"height":80};
const content = `<g class="cuyn6tgcc"><path class="rmanxnaqh"/><path clip-rule="evenodd" class="h8v7_hsyz"/><path class="tktzuhbfv"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="glyphs:image-bold" /></template>
