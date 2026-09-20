<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/r/rj_svym1d.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":48,"height":48};
const content = `<path class="rj_svym1d"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="streamline-plump:arrow-cursor-1-solid" /></template>
