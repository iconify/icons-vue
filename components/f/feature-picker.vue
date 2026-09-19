<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/s/su9dnwgms.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":32,"height":32};
const content = `<path class="su9dnwgms"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="carbon:feature-picker" /></template>
