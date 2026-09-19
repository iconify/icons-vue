<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/h/hx8n5wbth.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="hx8n5wbth"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="hugeicons:horse-head" /></template>
