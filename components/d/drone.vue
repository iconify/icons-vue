<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/a/aro0gib6h.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":48,"height":48};
const content = `<path class="aro0gib6h"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="icon-park-outline:drone" /></template>
