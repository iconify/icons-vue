<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/h/h45h-ybpu.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="h45h-ybpu"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="bx:bxs-car-mechanic" /></template>
