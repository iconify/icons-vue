<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/o/ou-cxiblp.css';
import '../../css/j/jheawubao.css';
import '../../css/h/h1a11qb_c.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":48,"height":48};
const content = `<path class="ou-cxiblp"/><path class="jheawubao"/><path class="h1a11qb_c"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="energy-icons:gas-valve-48" /></template>
