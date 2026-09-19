<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/j/j1alc3bdk.css';
import '../../css/u/uborx5bey.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":32,"height":32};
const content = `<path class="j1alc3bdk"/><path class="uborx5bey"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="carbon:cloud-download" /></template>
