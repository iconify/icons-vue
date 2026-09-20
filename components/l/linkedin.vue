<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/j/j4uo-0s9d.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="j4uo-0s9d"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="pixelarticons:linkedin" /></template>
