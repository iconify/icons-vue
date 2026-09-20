<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/o/ouu7mgbov.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="ouu7mgbov"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="pixelarticons:attachment" /></template>
