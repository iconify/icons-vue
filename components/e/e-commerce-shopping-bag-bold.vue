<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/k/ksr103b_e.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="ksr103b_e"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="streamline-ultimate:e-commerce-shopping-bag-bold" /></template>
