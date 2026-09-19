<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/h/h-rttbbcm.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":16,"height":16};
const content = `<path class="h-rttbbcm"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="garden:heading-stroke-16" /></template>
