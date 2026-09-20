<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/u/u0_h-gb7w.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":22,"height":22};
const content = `<path class="u0_h-gb7w"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="memory:box-light-double-horizontal-down" /></template>
