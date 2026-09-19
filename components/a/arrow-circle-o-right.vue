<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/i/iqjhhacny.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":1536,"height":1536};
const content = `<g transform="translate(1536 0) scale(-1 1)"><path class="iqjhhacny"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="fa:arrow-circle-o-right" /></template>
