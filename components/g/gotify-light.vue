<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/l/l07xxkbqg.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":500,"height":500};
const content = `<path class="l07xxkbqg"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="selfhst:gotify-light" /></template>
