<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/u/usv4oibvc.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="usv4oibvc"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="mdi:chat-remove" /></template>
