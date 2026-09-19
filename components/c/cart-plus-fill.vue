<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/m/mhm26nblu.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":16,"height":16};
const content = `<path class="mhm26nblu"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="bi:cart-plus-fill" /></template>
