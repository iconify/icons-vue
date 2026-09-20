<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/v/vqiytfyza.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="vqiytfyza"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="streamline-logos:google-drive-logo-1" /></template>
