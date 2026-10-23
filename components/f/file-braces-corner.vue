<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/w/wef_rfbrt.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="wef_rfbrt"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="vadivam:file-braces-corner" /></template>
