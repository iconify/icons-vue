<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/j/jqe6l8ger.css';
import '../../css/v/vzdt97b6q.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":48,"height":48};
const content = `<path class="jqe6l8ger"/><path class="vzdt97b6q"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="energy-icons:corner-right-down-48-bold" /></template>
