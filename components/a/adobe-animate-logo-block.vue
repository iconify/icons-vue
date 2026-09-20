<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/s/sh-974bjo.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path clip-rule="evenodd" class="sh-974bjo"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="streamline-logos:adobe-animate-logo-block" /></template>
