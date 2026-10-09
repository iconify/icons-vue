<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/o/ona24jwrs.css';
import '../../css/x/x1xwve8uf.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":48,"height":48};
const content = `<path class="ona24jwrs"/><path class="x1xwve8uf"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="energy-icons:cast-48-bold" /></template>
