<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/r/rv2g9obeh.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":20,"height":20};
const content = `<path class="rv2g9obeh"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="zondicons:exclamation-outline" /></template>
