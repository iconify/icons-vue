<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/v/vmxo0ve4h.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="vmxo0ve4h"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="mingcute:antenna-line" /></template>
