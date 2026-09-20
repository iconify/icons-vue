<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/v/vek31jble.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="vek31jble"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="uil:left-arrow-to-left" /></template>
