<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/c/cuyn6tgcc.css';
import '../../css/g/g3kpjqbfy.css';
import '../../css/t/tgug5f0tr.css';
import '../../css/w/wmhvhjlfj.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":32,"height":32};
const content = `<g class="cuyn6tgcc"><path class="g3kpjqbfy"/><path class="tgug5f0tr"/><path class="wmhvhjlfj"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="fluent-emoji-high-contrast:japanese-congratulations-button" /></template>
