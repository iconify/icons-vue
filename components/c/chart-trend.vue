<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/p/p5fi-nhgh.css';
import '../../css/s/s8x-bmb6i.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="p5fi-nhgh"/><path class="s8x-bmb6i"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="boxicons:chart-trend" /></template>
