<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/u/ub3v3v1ee.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="ub3v3v1ee"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="pixelarticons:checkbox-on" /></template>
