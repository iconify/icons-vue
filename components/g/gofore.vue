<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/a/azq1udcyj.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":640,"height":640};
const content = `<path class="azq1udcyj"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="fa7-brands:gofore" /></template>
