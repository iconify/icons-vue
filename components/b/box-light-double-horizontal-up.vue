<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/v/vwi067x_n.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":22,"height":22};
const content = `<path class="vwi067x_n"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="memory:box-light-double-horizontal-up" /></template>
