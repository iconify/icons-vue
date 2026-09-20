<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/s/sh6v-h_xx.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="sh6v-h_xx"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="mdi:camera-iris" /></template>
