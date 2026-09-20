<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/u/usb24irbq.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="usb24irbq"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="ri:compass-4-fill" /></template>
