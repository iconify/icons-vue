<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/g/gpu-awb2r.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="gpu-awb2r"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="ri:car-fill" /></template>
