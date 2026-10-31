<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/a/al_q3lsyt.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="al_q3lsyt"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="coolicons:bookmark-minus-round" /></template>
