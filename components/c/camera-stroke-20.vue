<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/z/zrvv8ub0p.css';
import '../../css/w/w0l__2bcq.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":20,"height":20};
const content = `<path class="zrvv8ub0p"/><path class="w0l__2bcq"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="garden:camera-stroke-20" /></template>
