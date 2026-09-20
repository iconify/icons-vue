<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/v/v1ya0l6ez.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":22,"height":22};
const content = `<path class="v1ya0l6ez"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="memory:box-light-down-right-stipple-inner" /></template>
