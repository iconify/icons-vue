<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/f/f48o6q92l.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="f48o6q92l"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="mdi:countertop-outline" /></template>
