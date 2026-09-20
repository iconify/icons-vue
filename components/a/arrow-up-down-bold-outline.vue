<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/d/d7z4fccwr.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="d7z4fccwr"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="mdi:arrow-up-down-bold-outline" /></template>
