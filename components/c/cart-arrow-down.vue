<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/f/f5mkhfblx.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":1664,"height":1408};
const content = `<path class="f5mkhfblx"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="fa:cart-arrow-down" /></template>
