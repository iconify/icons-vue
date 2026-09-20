<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/g/gxysq13ai.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="gxysq13ai"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="mdi:download-off" /></template>
