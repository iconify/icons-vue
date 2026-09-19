<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/e/emmkfnnhg.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":32,"height":32};
const content = `<path class="emmkfnnhg"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="carbon:currency-lira" /></template>
