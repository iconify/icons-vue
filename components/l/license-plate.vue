<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/u/u90bv9bth.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":256,"height":256};
const content = `<path class="u90bv9bth"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="pullo:license-plate" /></template>
