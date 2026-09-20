<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/j/jsohb8bgl.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="jsohb8bgl"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="mdi:chat-sleep-outline" /></template>
