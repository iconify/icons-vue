<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/c/cuyn6tgcc.css';
import '../../css/b/brf0aybbd.css';
import '../../css/a/aumkuub3x.css';
import '../../css/f/f4u25_1js.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":32,"height":32};
const content = `<g class="cuyn6tgcc"><path class="brf0aybbd"/><path class="aumkuub3x"/><path class="f4u25_1js"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="fluent-emoji-high-contrast:gear" /></template>
