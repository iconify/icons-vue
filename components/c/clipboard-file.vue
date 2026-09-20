<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/m/miql4qbpb.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="miql4qbpb"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="mdi:clipboard-file" /></template>
