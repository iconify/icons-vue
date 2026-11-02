<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/i/ie-k0yygp.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="ie-k0yygp"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="mingcute:fried-egg-line" /></template>
