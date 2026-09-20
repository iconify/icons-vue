<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/j/jhv95j8ok.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="jhv95j8ok"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="mdi:head-bulb-outline" /></template>
