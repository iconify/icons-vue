<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/m/mwuu-kkit.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="mwuu-kkit"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="mingcute:check-line-fill" /></template>
