<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/v/v0h0z9bsl.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":32,"height":32};
const content = `<path class="v0h0z9bsl"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="carbon:ibm-streamsets" /></template>
