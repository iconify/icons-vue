<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/v/vsh8bwo5w.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="vsh8bwo5w"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="coolicons:bookmark-off-fill-round" /></template>
