<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/r/r2isvmm5f.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":512,"height":512};
const content = `<path class="r2isvmm5f"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="fa6-solid:chart-line" /></template>
