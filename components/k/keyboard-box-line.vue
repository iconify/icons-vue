<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/i/i2etimw2x.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="i2etimw2x"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="ri:keyboard-box-line" /></template>
