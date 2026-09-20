<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/m/mp-0d0ifd.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="mp-0d0ifd"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="mdi:gate-arrow-right" /></template>
