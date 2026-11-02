<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/r/rtxtkocwh.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="rtxtkocwh"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="mingcute:flower-2-line" /></template>
