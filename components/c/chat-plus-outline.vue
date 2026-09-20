<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/h/huer_3mri.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="huer_3mri"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="mdi:chat-plus-outline" /></template>
