<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/o/ou56esbxa.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="ou56esbxa"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="ri:image-download-line" /></template>
