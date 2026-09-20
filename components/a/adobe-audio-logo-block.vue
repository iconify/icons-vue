<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/s/s21ugbb-p.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path clip-rule="evenodd" class="s21ugbb-p"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="streamline-logos:adobe-audio-logo-block" /></template>
