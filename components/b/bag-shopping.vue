<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/k/k1b4mfpxj.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":448,"height":512};
const content = `<path class="k1b4mfpxj"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="fa6-solid:bag-shopping" /></template>
