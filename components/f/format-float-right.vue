<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/n/n8d2qdqot.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="n8d2qdqot"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="mdi:format-float-right" /></template>
