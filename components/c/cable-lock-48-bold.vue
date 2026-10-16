<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/t/t0v50k2an.css';
import '../../css/x/xwaa6bbbm.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":48,"height":48};
const content = `<path class="t0v50k2an"/><path class="xwaa6bbbm"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="energy-icons:cable-lock-48-bold" /></template>
