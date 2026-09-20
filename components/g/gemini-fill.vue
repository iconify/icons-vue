<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/k/kwroy4t3p.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="kwroy4t3p"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="ri:gemini-fill" /></template>
