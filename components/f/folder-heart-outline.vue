<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/q/q_k6yvtja.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="q_k6yvtja"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="mdi:folder-heart-outline" /></template>
