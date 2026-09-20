<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/d/d15xdo0sw.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="d15xdo0sw"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="streamline-logos:google-plus-logo-2-solid" /></template>
