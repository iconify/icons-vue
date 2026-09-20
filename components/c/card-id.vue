<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/m/mcaqm5mvv.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="mcaqm5mvv"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="pixelarticons:card-id" /></template>
