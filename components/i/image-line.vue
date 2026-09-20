<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/j/j38gmm_ws.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="j38gmm_ws"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="ri:image-line" /></template>
