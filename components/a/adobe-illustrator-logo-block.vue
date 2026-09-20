<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/h/h8gz3gbai.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path clip-rule="evenodd" class="h8gz3gbai"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="streamline-logos:adobe-illustrator-logo-block" /></template>
