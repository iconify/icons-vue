<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/n/nwi5c5bur.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":48,"height":48};
const content = `<path class="nwi5c5bur"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="icon-park-outline:check" /></template>
