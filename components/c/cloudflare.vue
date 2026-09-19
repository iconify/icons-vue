<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/i/i80je-abe.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="i80je-abe"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="bxl:cloudflare" /></template>
