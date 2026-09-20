<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/d/dad9_nbwf.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":22,"height":22};
const content = `<path class="dad9_nbwf"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="memory:box-light-horizontal-up-stipple-up" /></template>
