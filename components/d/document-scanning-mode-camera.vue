<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/g/g_kn1vbbh.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="g_kn1vbbh"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="streamline-ultimate:document-scanning-mode-camera" /></template>
