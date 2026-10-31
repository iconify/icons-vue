<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/a/aovi3obji.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="aovi3obji"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="coolicons:circle-dot-fill-round" /></template>
