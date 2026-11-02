<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/m/m24q4o26z.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="m24q4o26z"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="mingcute:boom-box-fill" /></template>
