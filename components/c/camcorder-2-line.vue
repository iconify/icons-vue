<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/m/m9bn8ob3m.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="m9bn8ob3m"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="mingcute:camcorder-2-line" /></template>
