<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/r/r6-2_0kgl.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="r6-2_0kgl"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="mingcute:camera-rotate-line" /></template>
