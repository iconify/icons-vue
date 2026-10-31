<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/u/upwv21bcp.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="upwv21bcp"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="withicons:align-right-gloss" /></template>
