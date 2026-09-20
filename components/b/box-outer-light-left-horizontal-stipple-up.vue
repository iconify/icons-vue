<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/m/mt4qfkute.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":22,"height":22};
const content = `<path class="mt4qfkute"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="memory:box-outer-light-left-horizontal-stipple-up" /></template>
