<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/m/m-8x0x0fo.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":15,"height":15};
const content = `<path class="m-8x0x0fo"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="pinhead:circular-pill-and-capsule-pill" /></template>
