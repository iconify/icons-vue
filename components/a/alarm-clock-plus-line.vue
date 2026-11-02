<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/m/m5p5ygb5t.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="m5p5ygb5t"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="mingcute:alarm-clock-plus-line" /></template>
