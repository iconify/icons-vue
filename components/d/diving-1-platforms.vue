<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/o/oz4z-d47e.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":16,"height":16};
const content = `<path class="oz4z-d47e"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="roentgen:diving-1-platforms" /></template>
