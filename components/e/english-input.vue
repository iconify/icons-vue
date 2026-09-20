<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/d/dj8g4n60a.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="dj8g4n60a"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="ri:english-input" /></template>
