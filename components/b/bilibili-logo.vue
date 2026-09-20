<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/h/h01tyzbfu.css';
import '../../css/m/my5gt4brc.css';
import '../../css/h/h36pi06vn.css';
import '../../css/j/jqftzccni.css';
import '../../css/y/ymo2a1b_n.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="h01tyzbfu"><path class="my5gt4brc"/><path class="h36pi06vn"/><path class="jqftzccni"/><path class="ymo2a1b_n"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="streamline-logos:bilibili-logo" /></template>
