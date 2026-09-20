<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/v/v-h2_abdh.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="v-h2_abdh"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="mdi:clear-reverse-outline" /></template>
