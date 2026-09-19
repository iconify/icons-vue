<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/y/y5df2yblt.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":16,"height":16};
const content = `<path class="y5df2yblt"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="bi:code" /></template>
