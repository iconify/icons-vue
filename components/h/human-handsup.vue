<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/s/stkrjy51o.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="stkrjy51o"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="pixelarticons:human-handsup" /></template>
