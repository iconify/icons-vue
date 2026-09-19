<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/z/zo-k-6ycf.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="zo-k-6ycf"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="iconamoon:arrow-left-3-square-bold" /></template>
