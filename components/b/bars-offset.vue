<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/w/wwvp95byt.css';
import '../../css/l/le8r1fb7t.css';
import '../../css/z/z8_yi4bim.css';
import '../../css/j/jv95subdn.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":80,"height":80};
const content = `<g class="wwvp95byt"><path class="le8r1fb7t"/><path class="z8_yi4bim"/><path class="jv95subdn"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="glyphs-poly:bars-offset" /></template>
