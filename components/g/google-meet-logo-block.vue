<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/y/yv4v3ab7p.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path clip-rule="evenodd" class="yv4v3ab7p"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="streamline-logos:google-meet-logo-block" /></template>
