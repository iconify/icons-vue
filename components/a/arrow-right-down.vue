<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/w/wfsvs7kjx.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":48,"height":48};
const content = `<path class="wfsvs7kjx"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="icon-park-outline:arrow-right-down" /></template>
