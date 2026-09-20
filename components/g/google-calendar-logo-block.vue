<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/o/ok93i9baq.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path clip-rule="evenodd" class="ok93i9baq"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="streamline-logos:google-calendar-logo-block" /></template>
