<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/r/rem292bvp.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":22,"height":22};
const content = `<path class="rem292bvp"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="memory:box-outer-light-up-vertical-stipple-left" /></template>
