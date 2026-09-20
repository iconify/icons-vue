<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/r/ru3v4xl0x.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="ru3v4xl0x"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="mdi:egg-off" /></template>
