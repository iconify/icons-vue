<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/m/m0nttob5e.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":2368,"height":1664};
const content = `<path class="m0nttob5e"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="vs:cc-card" /></template>
