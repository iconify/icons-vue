<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/k/ky5bn3bkf.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path clip-rule="evenodd" class="ky5bn3bkf"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="streamline-logos:google-hangouts-chat-logo-block" /></template>
