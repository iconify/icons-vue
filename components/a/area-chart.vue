<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/m/mc5usib6x.css';
import '../../css/j/j2plu7b6v.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":48,"height":48};
const content = `<path class="mc5usib6x"/><path class="j2plu7b6v"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="flat-color-icons:area-chart" /></template>
