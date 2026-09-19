<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/s/svg3_r69m.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":1664,"height":1664};
const content = `<path class="svg3_r69m"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="fa:glass" /></template>
