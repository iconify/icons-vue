<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/s/s9n8h903w.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="s9n8h903w"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="pixelarticons:align-vertical-justify-center" /></template>
