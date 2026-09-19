<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/q/q4nbh2ges.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="q4nbh2ges"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="iconamoon:bluetooth" /></template>
