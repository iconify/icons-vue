<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/q/qetzpaczm.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":48,"height":48};
const content = `<path class="qetzpaczm"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="icon-park-outline:import-and-export" /></template>
