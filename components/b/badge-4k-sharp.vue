<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/o/otjmwacby.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="otjmwacby"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="pixelarticons:badge-4k-sharp" /></template>
