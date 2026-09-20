<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/u/unsftc1qj.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":14,"height":14};
const content = `<path class="unsftc1qj"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="streamline-color:arrow-down-dashed-square" /></template>
