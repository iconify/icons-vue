<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/c/cuyn6tgcc.css';
import '../../css/a/azeq84zvv.css';
import '../../css/m/mponw-bea.css';
import '../../css/a/a07ya4bgw.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":20,"height":20};
const content = `<g class="cuyn6tgcc"><path class="azeq84zvv"/><path clip-rule="evenodd" class="mponw-bea"/><path class="a07ya4bgw"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="pepicons-pencil:file" /></template>
