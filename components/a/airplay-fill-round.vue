<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/b/bym8_6bag.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="bym8_6bag"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="coolicons:airplay-fill-round" /></template>
