<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/n/nw67kyv5m.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":48,"height":48};
const content = `<path class="nw67kyv5m"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="energy-icons:chevrons-up-down-48" /></template>
