<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/v/vvg9x3bmc.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="vvg9x3bmc"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="mingcute:ferris-wheel-line" /></template>
