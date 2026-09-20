<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/y/yr0ffdc1x.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":16,"height":16};
const content = `<path class="yr0ffdc1x"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="lsicon:fire-outline" /></template>
