<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/j/jd8dqt85z.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="jd8dqt85z"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="coolicons:hexagon-duocolor-round" /></template>
