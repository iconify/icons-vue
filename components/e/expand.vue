<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/e/e0pyjrbcy.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="e0pyjrbcy"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="pixelarticons:expand" /></template>
