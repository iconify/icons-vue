<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/s/s8_6edc4d.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path clip-rule="evenodd" class="s8_6edc4d"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="mingcute:ebike-fill" /></template>
