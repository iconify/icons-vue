<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/v/vcl4k4fpu.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="vcl4k4fpu"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="mdi:arrow-right-bold-circle-outline" /></template>
