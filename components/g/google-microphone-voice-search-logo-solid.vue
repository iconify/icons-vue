<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/s/s3efznb-i.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path clip-rule="evenodd" class="s3efznb-i"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="streamline-logos:google-microphone-voice-search-logo-solid" /></template>
