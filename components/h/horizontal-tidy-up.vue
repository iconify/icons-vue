<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/a/aggw3hbin.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":48,"height":48};
const content = `<path class="aggw3hbin"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="icon-park-solid:horizontal-tidy-up" /></template>
