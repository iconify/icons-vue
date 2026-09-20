<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/i/i0y6x2b4e.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="i0y6x2b4e"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="streamline-ultimate:google-assistant-logo" /></template>
