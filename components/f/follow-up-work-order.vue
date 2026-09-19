<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/r/rktkv5b4x.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":32,"height":32};
const content = `<path class="rktkv5b4x"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="carbon:follow-up-work-order" /></template>
