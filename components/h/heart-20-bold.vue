<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/y/yp3hv2d4a.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":20,"height":20};
const content = `<path class="yp3hv2d4a"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="energy-icons:heart-20-bold" /></template>
