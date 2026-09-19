<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/j/j39ox-dfp.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":32,"height":32};
const content = `<path class="j39ox-dfp"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="carbon:energy-renewable" /></template>
