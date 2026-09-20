<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/n/nneu5acyn.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="nneu5acyn"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="mdi:database-export-outline" /></template>
