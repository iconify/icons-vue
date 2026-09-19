<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/c/cuyn6tgcc.css';
import '../../css/h/h9fxioceu.css';
import '../../css/o/oobt47bdu.css';
import '../../css/b/bkqbhrlym.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":32,"height":32};
const content = `<g class="cuyn6tgcc"><path class="h9fxioceu"/><path class="oobt47bdu"/><path class="bkqbhrlym"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="fluent-emoji-high-contrast:japanese-passing-grade-button" /></template>
