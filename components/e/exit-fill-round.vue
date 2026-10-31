<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/b/by6h6166w.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="by6h6166w"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="coolicons:exit-fill-round" /></template>
