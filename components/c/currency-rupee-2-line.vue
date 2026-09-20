<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/i/iv405_04e.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="iv405_04e"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="mingcute:currency-rupee-2-line" /></template>
