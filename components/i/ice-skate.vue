<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/v/vq-g64b7e.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="vq-g64b7e"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="lucide-lab:ice-skate" /></template>
