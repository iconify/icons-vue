<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/h/h01tyzbfu.css';
import '../../css/n/nnc71dbsl.css';
import '../../css/i/imnimkbei.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":16,"height":16};
const content = `<g class="h01tyzbfu"><path class="nnc71dbsl"/><path class="imnimkbei"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="lsicon:circle-star-outline" /></template>
