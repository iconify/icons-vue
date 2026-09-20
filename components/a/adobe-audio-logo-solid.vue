<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/i/i4d9iffrr.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path clip-rule="evenodd" class="i4d9iffrr"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="streamline-logos:adobe-audio-logo-solid" /></template>
