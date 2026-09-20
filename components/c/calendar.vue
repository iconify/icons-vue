<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/t/t3ad9wi7o.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="t3ad9wi7o"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="pixelarticons:calendar" /></template>
