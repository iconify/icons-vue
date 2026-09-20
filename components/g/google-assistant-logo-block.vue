<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/y/ysun414lb.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path clip-rule="evenodd" class="ysun414lb"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="streamline-logos:google-assistant-logo-block" /></template>
