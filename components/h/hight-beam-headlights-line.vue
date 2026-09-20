<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/e/eci9ug11m.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="eci9ug11m"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="mingcute:hight-beam-headlights-line" /></template>
