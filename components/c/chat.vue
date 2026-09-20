<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/d/dq2rymb7m.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="dq2rymb7m"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="pixelarticons:chat" /></template>
