<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/c/cuyn6tgcc.css';
import '../../css/e/e18ow5b9y.css';
import '../../css/q/qgvdpubqe.css';
import '../../css/y/y66soqbdl.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":80,"height":80};
const content = `<g class="cuyn6tgcc"><path clip-rule="evenodd" class="e18ow5b9y"/><path clip-rule="evenodd" class="qgvdpubqe"/><path class="y66soqbdl"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="glyphs:envelope-open-note-bold" /></template>
