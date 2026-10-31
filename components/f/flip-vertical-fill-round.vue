<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/q/qfsnvedme.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="qfsnvedme"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="coolicons:flip-vertical-fill-round" /></template>
