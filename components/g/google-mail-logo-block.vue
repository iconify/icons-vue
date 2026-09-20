<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/y/yf8h-u92t.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path clip-rule="evenodd" class="yf8h-u92t"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="streamline-logos:google-mail-logo-block" /></template>
