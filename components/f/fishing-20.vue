<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/g/gxgw5_bly.css';
import '../../css/f/f1to3eutu.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":20,"height":20};
const content = `<path class="gxgw5_bly"/><path class="f1to3eutu"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="energy-icons:fishing-20" /></template>
