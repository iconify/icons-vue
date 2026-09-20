<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/d/d44wotzbb.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":20,"height":20};
const content = `<path class="d44wotzbb"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="ooui:funnel" /></template>
