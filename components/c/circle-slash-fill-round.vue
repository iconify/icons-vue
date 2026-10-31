<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/f/fgvuc9pkq.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="fgvuc9pkq"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="coolicons:circle-slash-fill-round" /></template>
