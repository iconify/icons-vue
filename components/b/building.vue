<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/l/l_n2pacdg.css';
import '../../css/x/xsa49xbtj.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":32,"height":32};
const content = `<path class="l_n2pacdg"/><path class="xsa49xbtj"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="carbon:building" /></template>
