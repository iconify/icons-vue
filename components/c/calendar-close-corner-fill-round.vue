<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/b/bd2zb8b0r.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="bd2zb8b0r"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="coolicons:calendar-close-corner-fill-round" /></template>
