<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/w/w_6t__bku.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="w_6t__bku"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="pixelarticons:ai-scan" /></template>
