<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/b/bg-0uvb6x.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":22,"height":22};
const content = `<path class="bg-0uvb6x"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="memory:box-outer-light-left-horizontal-stipple-down" /></template>
