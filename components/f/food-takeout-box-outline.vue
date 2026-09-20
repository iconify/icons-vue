<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/y/y00yb5b9o.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="y00yb5b9o"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="mdi:food-takeout-box-outline" /></template>
