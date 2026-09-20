<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/h/h-a3-_mce.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="h-a3-_mce"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="mdi:av-timer" /></template>
