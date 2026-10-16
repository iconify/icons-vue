<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/s/s8m_o6v-h.css';
import '../../css/a/arhsv8bbj.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":20,"height":20};
const content = `<path class="s8m_o6v-h"/><path class="arhsv8bbj"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="energy-icons:bungalow-20-bold" /></template>
