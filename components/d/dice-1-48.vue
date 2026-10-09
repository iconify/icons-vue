<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/l/lr7h2fb6d.css';
import '../../css/s/svhavybtd.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":48,"height":48};
const content = `<path class="lr7h2fb6d"/><path class="svhavybtd"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="energy-icons:dice-1-48" /></template>
