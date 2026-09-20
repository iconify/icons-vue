<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/m/m-4l5nx5i.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path clip-rule="evenodd" class="m-4l5nx5i"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="mingcute:candle-fill" /></template>
