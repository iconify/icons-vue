<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/r/rgi2k-5vf.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":32,"height":32};
const content = `<path class="rgi2k-5vf"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="carbon:deployment-unit-technical-installation" /></template>
