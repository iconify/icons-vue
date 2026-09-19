<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/s/spirfzv-y.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":32,"height":32};
const content = `<path class="spirfzv-y"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="carbon:ibm-cloud-subnets" /></template>
