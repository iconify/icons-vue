<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/g/gsme-bm6g.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="gsme-bm6g"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="mingcute:celsius-fill" /></template>
