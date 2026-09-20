<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/s/sersdwbah.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="sersdwbah"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="mingcute:camcorder-3-fill" /></template>
