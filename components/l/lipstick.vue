<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/e/ekt5e2b3e.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":48,"height":48};
const content = `<path class="ekt5e2b3e"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="icon-park-outline:lipstick" /></template>
