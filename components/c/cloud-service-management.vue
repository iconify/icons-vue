<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/c/cl8z71bau.css';
import '../../css/y/yfddwd_7g.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":32,"height":32};
const content = `<path class="cl8z71bau"/><path class="yfddwd_7g"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="carbon:cloud-service-management" /></template>
