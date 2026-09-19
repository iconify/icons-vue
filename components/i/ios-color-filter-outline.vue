<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/x/xl-6btjno.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":512,"height":512};
const content = `<path class="xl-6btjno"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="ion:ios-color-filter-outline" /></template>
