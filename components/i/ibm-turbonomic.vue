<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/h/h811jub2x.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":32,"height":32};
const content = `<path class="h811jub2x"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="carbon:ibm-turbonomic" /></template>
