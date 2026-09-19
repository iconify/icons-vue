<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/r/r69d1vbfv.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":32,"height":32};
const content = `<path class="r69d1vbfv"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="carbon:array" /></template>
