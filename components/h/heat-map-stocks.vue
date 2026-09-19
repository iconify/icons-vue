<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/e/e6xhyebnf.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":32,"height":32};
const content = `<path class="e6xhyebnf"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="carbon:heat-map-stocks" /></template>
