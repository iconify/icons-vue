<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/p/p5k9mk7lh.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="p5k9mk7lh"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="ri:airplay-line" /></template>
