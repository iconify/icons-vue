<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/m/mq7e6332b.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path clip-rule="evenodd" class="mq7e6332b"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="solar:bedside-table-3-outline" /></template>
