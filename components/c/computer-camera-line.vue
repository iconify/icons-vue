<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/l/ldzt82bcc.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="ldzt82bcc"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="mingcute:computer-camera-line" /></template>
