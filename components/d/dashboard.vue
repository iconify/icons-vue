<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/d/d8yr_-b9y.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":8,"height":8};
const content = `<path class="d8yr_-b9y"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="oi:dashboard" /></template>
