<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/g/gt_hpirfh.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":22,"height":22};
const content = `<path class="gt_hpirfh"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="memory:alpha-s" /></template>
