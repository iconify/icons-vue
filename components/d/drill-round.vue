<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/h/h52qjsb9w.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="h52qjsb9w"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="coolicons:drill-round" /></template>
