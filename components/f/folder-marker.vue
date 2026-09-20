<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/f/fidx61bnr.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="fidx61bnr"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="mdi:folder-marker" /></template>
