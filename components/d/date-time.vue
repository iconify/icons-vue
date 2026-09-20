<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/s/se4v5wb1x.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="se4v5wb1x"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="pixelarticons:date-time" /></template>
