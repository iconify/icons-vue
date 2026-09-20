<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/n/ntenuzt3s.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="ntenuzt3s"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="ri:brush-line" /></template>
