<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/r/rmh5xkboo.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":22,"height":22};
const content = `<path class="rmh5xkboo"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="memory:box-outer-light-left-horizontal-stipple" /></template>
