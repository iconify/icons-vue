<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/f/fesfmrsef.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="fesfmrsef"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="mingcute:heavy-snowstorm-line" /></template>
