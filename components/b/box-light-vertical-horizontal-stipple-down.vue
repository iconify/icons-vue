<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/f/f00xnhb_k.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":22,"height":22};
const content = `<path class="f00xnhb_k"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="memory:box-light-vertical-horizontal-stipple-down" /></template>
