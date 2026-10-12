<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/t/tpblfybed.css';
import '../../css/u/usk21pbsg.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":48,"height":48};
const content = `<path class="tpblfybed"/><path class="usk21pbsg"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="energy-icons:acorn-48-bold" /></template>
