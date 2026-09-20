<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/k/kra9o8bzf.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="kra9o8bzf"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="mdi:cog-sync-outline" /></template>
