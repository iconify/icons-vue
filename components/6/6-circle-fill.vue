<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/o/o3fklgb3y.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":16,"height":16};
const content = `<path class="o3fklgb3y"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="bi:6-circle-fill" /></template>
