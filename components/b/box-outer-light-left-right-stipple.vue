<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/z/zx8ai4b8y.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":22,"height":22};
const content = `<path class="zx8ai4b8y"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="memory:box-outer-light-left-right-stipple" /></template>
