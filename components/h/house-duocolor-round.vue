<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/g/gg8g3kb_x.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="gg8g3kb_x"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="coolicons:house-duocolor-round" /></template>
