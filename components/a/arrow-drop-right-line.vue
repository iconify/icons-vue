<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/h/hoit-5aey.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="hoit-5aey"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="ri:arrow-drop-right-line" /></template>
