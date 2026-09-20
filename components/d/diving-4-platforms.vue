<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/l/ljbrb5xyb.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":16,"height":16};
const content = `<path class="ljbrb5xyb"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="roentgen:diving-4-platforms" /></template>
