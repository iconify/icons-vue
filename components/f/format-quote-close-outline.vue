<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/k/kaq7q4l9s.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="kaq7q4l9s"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="mdi:format-quote-close-outline" /></template>
