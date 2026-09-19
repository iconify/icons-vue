<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/c/cuyn6tgcc.css';
import '../../css/f/fyxn4ccew.css';
import '../../css/d/di9ltg2bw.css';
import '../../css/s/saxggjx6e.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":32,"height":32};
const content = `<g class="cuyn6tgcc"><path class="fyxn4ccew"/><path class="di9ltg2bw"/><path class="saxggjx6e"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="fluent-emoji-high-contrast:hot-face" /></template>
