<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/n/ncjlt0bzz.css';
import '../../css/r/rvuq3ibhd.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":20,"height":20};
const content = `<path class="ncjlt0bzz"/><path class="rvuq3ibhd"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="energy-icons:dollar-20" /></template>
