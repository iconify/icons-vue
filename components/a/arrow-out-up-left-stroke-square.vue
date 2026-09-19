<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/j/j082ynusa.css';
import '../../css/l/lqhgtqdtq.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="j082ynusa"/><path class="lqhgtqdtq"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="boxicons:arrow-out-up-left-stroke-square" /></template>
