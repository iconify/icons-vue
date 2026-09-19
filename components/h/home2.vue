<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/d/dl5sv6bqj.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":16,"height":16};
const content = `<path class="dl5sv6bqj"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="icomoon-free:home2" /></template>
