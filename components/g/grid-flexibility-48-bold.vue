<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/j/jy2a-4big.css';
import '../../css/b/bj4r87yrk.css';
import '../../css/s/sha9b7rmw.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":48,"height":48};
const content = `<path class="jy2a-4big"/><path class="bj4r87yrk"/><path class="sha9b7rmw"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="energy-icons:grid-flexibility-48-bold" /></template>
