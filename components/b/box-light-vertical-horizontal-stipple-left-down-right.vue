<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/d/debshhs4b.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":22,"height":22};
const content = `<path class="debshhs4b"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="memory:box-light-vertical-horizontal-stipple-left-down-right" /></template>
