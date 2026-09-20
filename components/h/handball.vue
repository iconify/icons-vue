<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/s/skq6_k_9q.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="skq6_k_9q"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="mdi:handball" /></template>
