<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/d/dtdpcxepa.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="dtdpcxepa"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="ri:character-recognition-fill" /></template>
