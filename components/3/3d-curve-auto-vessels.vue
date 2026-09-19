<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/s/sxjnpbb5e.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":32,"height":32};
const content = `<path class="sxjnpbb5e"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="carbon:3d-curve-auto-vessels" /></template>
