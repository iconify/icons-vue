<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/z/z1g4vx_wr.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="z1g4vx_wr"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="mdi:folder-arrow-left" /></template>
