<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/r/rmob1ccvi.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="rmob1ccvi"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="mdi:horoscope-gemini" /></template>
