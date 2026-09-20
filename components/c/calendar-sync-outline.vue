<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/c/cpzpu_oja.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="cpzpu_oja"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="mdi:calendar-sync-outline" /></template>
