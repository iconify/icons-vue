<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/m/mgz0iz72w.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":480,"height":512};
const content = `<path class="mgz0iz72w"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="fa-solid:car-alt" /></template>
