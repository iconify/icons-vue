<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/f/ft5dv1b6b.css';
import '../../css/w/wjvia45sw.css';
import '../../css/t/tm8p9gwlr.css';
import '../../css/p/p8eiskbvq.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":80,"height":80};
const content = `<g class="ft5dv1b6b"><path class="wjvia45sw"/><path class="tm8p9gwlr"/><path class="p8eiskbvq"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="glyphs-poly:gift-1" /></template>
