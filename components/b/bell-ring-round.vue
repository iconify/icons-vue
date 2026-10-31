<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/d/db68k-bun.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="db68k-bun"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="coolicons:bell-ring-round" /></template>
