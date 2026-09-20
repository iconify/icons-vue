<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/y/yvtdb8fbm.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="yvtdb8fbm"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="streamline-ultimate:google-assistant-logo-bold" /></template>
