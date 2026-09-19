<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/n/n85e_ljup.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":32,"height":32};
const content = `<path class="n85e_ljup"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="carbon:crop-health" /></template>
