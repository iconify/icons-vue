<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/i/it6ez8b2l.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="it6ez8b2l"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="mingcute:layers-2-line" /></template>
