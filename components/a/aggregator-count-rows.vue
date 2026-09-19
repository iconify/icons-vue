<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/u/uabl71b1n.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":32,"height":32};
const content = `<path class="uabl71b1n"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="carbon:aggregator-count-rows" /></template>
