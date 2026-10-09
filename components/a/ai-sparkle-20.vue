<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/j/j1v56tbzq.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":20,"height":20};
const content = `<path class="j1v56tbzq"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="energy-icons:ai-sparkle-20" /></template>
