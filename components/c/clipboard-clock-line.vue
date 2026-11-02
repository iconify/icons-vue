<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/z/z_-6zsbtw.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="z_-6zsbtw"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="mingcute:clipboard-clock-line" /></template>
