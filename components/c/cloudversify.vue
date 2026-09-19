<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/m/miy_awb1i.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":616,"height":512};
const content = `<path class="miy_awb1i"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="fa6-brands:cloudversify" /></template>
