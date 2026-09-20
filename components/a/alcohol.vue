<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/h/h2x854sah.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="h2x854sah"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="mdi:alcohol" /></template>
