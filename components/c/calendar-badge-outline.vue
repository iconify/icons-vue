<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/e/e49arf_nc.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="e49arf_nc"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="mdi:calendar-badge-outline" /></template>
