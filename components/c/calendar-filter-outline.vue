<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/s/s4z_dubpd.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="s4z_dubpd"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="mdi:calendar-filter-outline" /></template>
