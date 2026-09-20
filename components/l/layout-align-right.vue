<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/r/roylc0i0s.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="roylc0i0s"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="pixelarticons:layout-align-right" /></template>
