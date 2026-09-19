<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/i/i9_r145xx.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":16,"height":16};
const content = `<path class="i9_r145xx"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="bi:briefcase" /></template>
