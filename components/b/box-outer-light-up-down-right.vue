<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/m/mtph6ub4q.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":22,"height":22};
const content = `<path class="mtph6ub4q"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="memory:box-outer-light-up-down-right" /></template>
