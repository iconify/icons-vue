<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/v/vx8aqt6mw.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="vx8aqt6mw"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="mdi:backspace-reverse" /></template>
