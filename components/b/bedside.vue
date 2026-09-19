<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/s/sd5t267ma.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":48,"height":48};
const content = `<path class="sd5t267ma"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="icon-park-outline:bedside" /></template>
