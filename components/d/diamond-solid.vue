<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/c/cno0gvqrq.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":32,"height":32};
const content = `<path class="cno0gvqrq"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="carbon:diamond-solid" /></template>
