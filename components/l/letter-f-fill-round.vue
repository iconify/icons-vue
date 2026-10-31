<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/s/sa6pubb4r.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="sa6pubb4r"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="coolicons:letter-f-fill-round" /></template>
