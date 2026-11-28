<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/r/rrxl9tfar.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="rrxl9tfar"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="noviair:car-check" /></template>
