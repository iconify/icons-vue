<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/w/wv4g6ebah.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="wv4g6ebah"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="coolicons:burger-fill-round" /></template>
