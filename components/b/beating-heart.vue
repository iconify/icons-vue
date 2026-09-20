<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/x/xdsnylbwc.css';
import '../../css/l/lb80qlbob.css';
import '../../css/k/ko1bcvb2i.css';
import '../../css/c/ct87dwbyc.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":72,"height":72};
const content = `<path class="xdsnylbwc"/><g class="lb80qlbob"><path class="ko1bcvb2i"/><path class="ct87dwbyc"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="openmoji:beating-heart" /></template>
