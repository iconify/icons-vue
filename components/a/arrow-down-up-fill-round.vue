<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/t/tj3yo8bxf.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="tj3yo8bxf"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="coolicons:arrow-down-up-fill-round" /></template>
