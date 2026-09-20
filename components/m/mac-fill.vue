<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/r/rcc80x6rx.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="rcc80x6rx"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="ri:mac-fill" /></template>
