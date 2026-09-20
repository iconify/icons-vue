<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/c/cs4b5vbze.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="cs4b5vbze"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="mdi:camera-outline" /></template>
