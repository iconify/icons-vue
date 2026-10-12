<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/e/esw9xfprr.css';
import '../../css/v/vo4v1ibev.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":20,"height":20};
const content = `<path class="esw9xfprr"/><path class="vo4v1ibev"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="garden:bubble-check-stroke-20" /></template>
