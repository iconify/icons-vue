<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/a/avtfwobpr.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="avtfwobpr"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="pixelarticons:add-box-multiple" /></template>
