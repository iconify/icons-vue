<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/i/i975fgb9j.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":48,"height":48};
const content = `<path class="i975fgb9j"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="icon-park:five" /></template>
