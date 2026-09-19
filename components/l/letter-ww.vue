<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/r/rmghfvc3e.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":32,"height":32};
const content = `<path class="rmghfvc3e"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="carbon:letter-ww" /></template>
