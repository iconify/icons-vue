<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/g/g2m4sxbuf.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="g2m4sxbuf"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="mdi:comma-box-outline" /></template>
