<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/d/dxlej5bwv.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":48,"height":48};
const content = `<path class="dxlej5bwv"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="icon-park-solid:good" /></template>
