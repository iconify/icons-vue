<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/d/d-22xbcav.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="d-22xbcav"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="coolicons:circle-sparkle-round" /></template>
