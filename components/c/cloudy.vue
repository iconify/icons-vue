<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/n/nc_42ccbj.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":16,"height":16};
const content = `<path class="nc_42ccbj"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="bi:cloudy" /></template>
