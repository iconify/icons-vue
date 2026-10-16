<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/y/yg5b9ebia.css';
import '../../css/h/hrfcglb8n.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":48,"height":48};
const content = `<path class="yg5b9ebia"/><path class="hrfcglb8n"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="energy-icons:bell-snooze-48-bold" /></template>
