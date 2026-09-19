<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/c/cuyn6tgcc.css';
import '../../css/l/lqtldpbjr.css';
import '../../css/z/zgpfknbfx.css';
import '../../css/a/ast-ebc7m.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":80,"height":80};
const content = `<g class="cuyn6tgcc"><path class="lqtldpbjr"/><path clip-rule="evenodd" class="zgpfknbfx"/><path class="ast-ebc7m"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="glyphs:bandage-bold" /></template>
