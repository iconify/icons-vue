<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/c/c3bv6j6bj.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":16,"height":16};
const content = `<path class="c3bv6j6bj"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="vaadin:line-bar-chart" /></template>
