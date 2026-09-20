<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/k/ki4-hdcdf.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="ki4-hdcdf"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="mingcute:large-arrow-left-line" /></template>
