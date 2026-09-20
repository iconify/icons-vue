<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/o/orkwv2bri.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="orkwv2bri"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="ri:calendar-close-line" /></template>
