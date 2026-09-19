<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/x/xc18gbb4w.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="xc18gbb4w"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="ci:chat-circle-add" /></template>
