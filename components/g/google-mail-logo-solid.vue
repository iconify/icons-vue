<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/v/vqt-0cbly.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path clip-rule="evenodd" class="vqt-0cbly"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="streamline-logos:google-mail-logo-solid" /></template>
