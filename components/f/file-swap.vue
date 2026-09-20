<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/h/h54sqzb_s.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="h54sqzb_s"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="mdi:file-swap" /></template>
