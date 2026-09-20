<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/i/igozymbvy.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="igozymbvy"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="mdi:camera-rear-variant" /></template>
