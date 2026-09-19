<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/r/rqfa9ttux.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":32,"height":32};
const content = `<path class="rqfa9ttux"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="carbon:letter-jj" /></template>
