<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/k/k4p3i9bxt.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":640,"height":512};
const content = `<path class="k4p3i9bxt"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="fa6-solid:building-wheat" /></template>
