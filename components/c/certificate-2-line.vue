<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/q/q679esbud.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="q679esbud"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="mingcute:certificate-2-line" /></template>
