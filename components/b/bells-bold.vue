<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/c/cuyn6tgcc.css';
import '../../css/v/vmnknnmuy.css';
import '../../css/p/pg98zb21c.css';
import '../../css/i/imszhdckf.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":80,"height":80};
const content = `<g class="cuyn6tgcc"><path class="vmnknnmuy"/><path class="pg98zb21c"/><path class="imszhdckf"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="glyphs:bells-bold" /></template>
