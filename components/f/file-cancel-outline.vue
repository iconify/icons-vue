<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/i/i-6j63-le.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="i-6j63-le"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="mdi:file-cancel-outline" /></template>
