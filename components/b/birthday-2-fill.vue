<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/e/edogw145l.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="edogw145l"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="mingcute:birthday-2-fill" /></template>
