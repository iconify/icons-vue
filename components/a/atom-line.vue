<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/i/i11dx0b2j.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="i11dx0b2j"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="ri:atom-line" /></template>
