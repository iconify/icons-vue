<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/s/sx77gjbod.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="sx77gjbod"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="mdi:dharma-wheel" /></template>
