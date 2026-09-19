<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/u/u5xy30yhx.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":48,"height":48};
const content = `<path class="u5xy30yhx"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="icon-park-outline:foot" /></template>
