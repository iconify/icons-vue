<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/y/yqbn5f49h.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":16,"height":16};
const content = `<path class="yqbn5f49h"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="bi:cart-dash-fill" /></template>
