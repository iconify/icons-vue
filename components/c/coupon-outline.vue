<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/y/y96e-6bmi.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":16,"height":16};
const content = `<path class="y96e-6bmi"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="lsicon:coupon-outline" /></template>
