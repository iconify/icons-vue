<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/t/ttl5mlb8n.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":15,"height":15};
const content = `<path class="ttl5mlb8n"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="pinhead:diamond" /></template>
