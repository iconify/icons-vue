<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/m/m178_g6sx.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":32,"height":32};
const content = `<path class="m178_g6sx"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="carbon:arrow-down" /></template>
