<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/m/m1_y4b3pi.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":21,"height":21};
const content = `<path class="m1_y4b3pi"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="system-uicons:heart-rate" /></template>
