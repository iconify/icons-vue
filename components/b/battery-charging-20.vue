<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/g/gb0-klyri.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="gb0-klyri"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="mdi:battery-charging-20" /></template>
