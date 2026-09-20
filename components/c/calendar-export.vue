<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/i/ikpc8_hum.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="ikpc8_hum"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="mdi:calendar-export" /></template>
