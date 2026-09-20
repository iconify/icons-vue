<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/f/fxvxqnbvd.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="fxvxqnbvd"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="pixelarticons:calendar-remove" /></template>
