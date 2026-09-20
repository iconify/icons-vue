<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/i/ip2018xng.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="ip2018xng"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="mdi:clock-time-five-outline" /></template>
