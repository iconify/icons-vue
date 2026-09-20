<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/l/lbmk7ebis.css';
import '../../css/n/nnln5nbkq.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":32,"height":32};
const content = `<path class="lbmk7ebis"/><path class="nnln5nbkq"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="streamline-pixel:ecology-wood-plant-grow" /></template>
