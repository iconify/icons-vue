<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/w/wk256nb0f.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="wk256nb0f"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="mdi:die-6" /></template>
