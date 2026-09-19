<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/c/cuyn6tgcc.css';
import '../../css/l/lgxdb5b3q.css';
import '../../css/z/zbihpnyml.css';
import '../../css/b/bkqbhrlym.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":32,"height":32};
const content = `<g class="cuyn6tgcc"><path class="lgxdb5b3q"/><path class="zbihpnyml"/><path class="bkqbhrlym"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="fluent-emoji-high-contrast:cancer" /></template>
