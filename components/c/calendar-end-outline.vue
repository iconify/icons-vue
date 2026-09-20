<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/p/p4ntoybtw.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="p4ntoybtw"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="mdi:calendar-end-outline" /></template>
