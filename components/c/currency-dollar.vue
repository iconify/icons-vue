<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/r/r07j-kbyx.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":20,"height":20};
const content = `<path class="r07j-kbyx"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="zondicons:currency-dollar" /></template>
