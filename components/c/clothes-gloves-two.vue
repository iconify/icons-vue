<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/a/a5zb4-b3y.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":48,"height":48};
const content = `<path class="a5zb4-b3y"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="icon-park-outline:clothes-gloves-two" /></template>
