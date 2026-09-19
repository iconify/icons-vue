<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/z/zon5_mjhb.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":16,"height":16};
const content = `<path class="zon5_mjhb"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="bi:emoji-expressionless-fill" /></template>
