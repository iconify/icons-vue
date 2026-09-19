<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/k/k4ycw1bvi.css';
import '../../css/r/r-n6f1bae.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="k4ycw1bvi"/><path class="r-n6f1bae"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="boxicons:arrow-out-up-right-stroke-square" /></template>
