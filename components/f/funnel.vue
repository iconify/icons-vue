<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/t/tu378pxim.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":15,"height":15};
const content = `<path class="tu378pxim"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="pinhead:funnel" /></template>
