<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/m/mwlhw678o.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="mwlhw678o"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="ri:chat-download-fill" /></template>
