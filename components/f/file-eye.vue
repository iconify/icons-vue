<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/n/nis2pu8ag.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="nis2pu8ag"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="mdi:file-eye" /></template>
