<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/z/z576df0bp.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":22,"height":22};
const content = `<path class="z576df0bp"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="memory:box-light-vertical-horizontal-stipple-down-left" /></template>
