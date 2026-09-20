<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/w/wpry1_b8x.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="wpry1_b8x"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="mdi:fan-plus" /></template>
