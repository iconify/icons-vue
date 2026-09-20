<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/h/h_lo8e9qu.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="h_lo8e9qu"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="mdi:cookie-outline" /></template>
