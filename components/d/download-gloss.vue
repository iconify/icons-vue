<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/p/p5_ay1m0z.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="p5_ay1m0z"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="withicons:download-gloss" /></template>
