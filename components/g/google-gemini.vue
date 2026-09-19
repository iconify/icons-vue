<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/h/hj-b23bfx.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="hj-b23bfx"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="hugeicons:google-gemini" /></template>
