<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/v/vmgtk8bav.css';
import '../../css/k/k4873id8y.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":48,"height":48};
const content = `<path class="vmgtk8bav"/><path class="k4873id8y"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="energy-icons:film-reel-48" /></template>
