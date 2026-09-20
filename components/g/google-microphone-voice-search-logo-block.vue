<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/s/s2jwt4bmx.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path clip-rule="evenodd" class="s2jwt4bmx"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="streamline-logos:google-microphone-voice-search-logo-block" /></template>
