<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/y/yf2m3cbtu.css';
import '../../css/q/q36jvnbvp.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":20,"height":20};
const content = `<path class="yf2m3cbtu"/><path class="q36jvnbvp"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="energy-icons:kanban-20" /></template>
