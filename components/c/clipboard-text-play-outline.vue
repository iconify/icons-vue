<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/z/z601x6bil.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="z601x6bil"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="mdi:clipboard-text-play-outline" /></template>
