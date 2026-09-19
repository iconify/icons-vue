<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/q/qkjp8n2ij.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="qkjp8n2ij"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="cbi:letsencrypt" /></template>
