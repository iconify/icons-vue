<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/s/s0rt-zb2s.css';
import '../../css/h/hgpzimtyu.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":32,"height":32};
const content = `<path class="s0rt-zb2s"/><path class="hgpzimtyu"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="carbon:chart-column-floating" /></template>
