<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/i/ie16_vbpg.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="ie16_vbpg"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="mdi:cloud-plus-outline" /></template>
