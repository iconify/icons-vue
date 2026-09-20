<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/u/uvl4abcut.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="uvl4abcut"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="mdi:hdmi-port" /></template>
