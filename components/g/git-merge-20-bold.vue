<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/u/u-5gvsbjv.css';
import '../../css/j/j89f_0dyx.css';
import '../../css/r/re3ef0big.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":20,"height":20};
const content = `<path class="u-5gvsbjv"/><path class="j89f_0dyx"/><path class="re3ef0big"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="energy-icons:git-merge-20-bold" /></template>
