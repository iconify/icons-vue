<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/j/jcyq56q4t.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="jcyq56q4t"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="pixelarticons:device-watch" /></template>
