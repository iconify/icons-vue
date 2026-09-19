<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/s/s4g-0aboz.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":48,"height":48};
const content = `<path class="s4g-0aboz"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="icon-park-outline:arrow-left-down" /></template>
