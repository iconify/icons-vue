<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/c/cuyn6tgcc.css';
import '../../css/f/fsk4bfdbc.css';
import '../../css/l/l2zp-wr5l.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":20,"height":20};
const content = `<g class="cuyn6tgcc"><path class="fsk4bfdbc"/><path clip-rule="evenodd" class="l2zp-wr5l"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="heroicons-solid:clipboard-check" /></template>
