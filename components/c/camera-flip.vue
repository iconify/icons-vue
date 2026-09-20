<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/a/aqk-0y0et.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="aqk-0y0et"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="mdi:camera-flip" /></template>
