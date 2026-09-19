<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/u/u_0g25s7o.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":32,"height":32};
const content = `<path class="u_0g25s7o"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="carbon:earth" /></template>
