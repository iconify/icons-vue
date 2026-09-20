<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/r/r49e0obzb.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="r49e0obzb"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="mdi:book-remove-outline" /></template>
