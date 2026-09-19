<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/l/leyai0bbf.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":48,"height":48};
const content = `<path class="leyai0bbf"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="icon-park-outline:hamburger-button" /></template>
