<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/d/djq87ob_p.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="djq87ob_p"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="si:chat-fill" /></template>
