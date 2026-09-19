<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/c/cuyn6tgcc.css';
import '../../css/u/ute87qmnh.css';
import '../../css/f/frswp0b7h.css';
import '../../css/f/f5f8fudfg.css';
import '../../css/b/b2mock0sg.css';
import '../../css/b/bwkigdc-a.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":80,"height":80};
const content = `<g class="cuyn6tgcc"><path clip-rule="evenodd" class="ute87qmnh"/><path class="frswp0b7h"/><path clip-rule="evenodd" class="f5f8fudfg"/><path class="b2mock0sg"/><path clip-rule="evenodd" class="bwkigdc-a"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="glyphs:box-open-bold" /></template>
