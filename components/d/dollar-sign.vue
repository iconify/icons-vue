<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/v/vk782fkpb.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="vk782fkpb"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="hugeicons:dollar-sign" /></template>
