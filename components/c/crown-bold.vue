<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/c/cuyn6tgcc.css';
import '../../css/j/jz143rbfe.css';
import '../../css/a/atekq_emk.css';
import '../../css/q/qse1po-lv.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":80,"height":80};
const content = `<g class="cuyn6tgcc"><path clip-rule="evenodd" class="jz143rbfe"/><rect class="atekq_emk"/><path clip-rule="evenodd" class="qse1po-lv"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="glyphs:crown-bold" /></template>
