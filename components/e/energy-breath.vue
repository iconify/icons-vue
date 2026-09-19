<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/x/xq3m9lb1e.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":512,"height":512};
const content = `<path class="xq3m9lb1e"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="game-icons:energy-breath" /></template>
