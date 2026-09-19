<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/q/q-cd4m-xs.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="q-cd4m-xs"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="guidance:left-angle-arrow" /></template>
