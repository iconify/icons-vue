<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/p/pd13eg0ma.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":48,"height":48};
const content = `<path class="pd13eg0ma"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="icon-park-solid:align-horizontal-center-two" /></template>
