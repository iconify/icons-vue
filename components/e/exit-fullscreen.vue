<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/q/q8kuy1ofz.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":20,"height":20};
const content = `<path class="q8kuy1ofz"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="ooui:exit-fullscreen" /></template>
