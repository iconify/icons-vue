<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/n/nivk-30wy.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":48,"height":48};
const content = `<path clip-rule="evenodd" class="nivk-30wy"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="icon-park-outline:cc" /></template>
