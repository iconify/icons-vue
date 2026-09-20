<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/w/wx-ljwbff.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="wx-ljwbff"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="mdi:circle-off-outline" /></template>
