<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/p/pzhf6mbgl.css';
import '../../css/d/d72ifg1in.css';
import '../../css/k/ko92zebxf.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":512,"height":512};
const content = `<path class="pzhf6mbgl"/><path class="d72ifg1in"/><path class="ko92zebxf"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="ion:ear-outline" /></template>
