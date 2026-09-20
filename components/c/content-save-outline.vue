<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/d/db3x8nb0r.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="db3x8nb0r"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="mdi:content-save-outline" /></template>
