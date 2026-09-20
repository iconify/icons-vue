<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/s/sq3o_nbxy.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":22,"height":22};
const content = `<path class="sq3o_nbxy"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="memory:box-light-dashed-vertical" /></template>
