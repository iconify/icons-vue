<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/l/l8r0qnbcn.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":48,"height":48};
const content = `<path class="l8r0qnbcn"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="icon-park-outline:center-alignment" /></template>
