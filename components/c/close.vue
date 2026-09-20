<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/c/chd-g8bzc.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":16,"height":16};
const content = `<path class="chd-g8bzc"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="vaadin:close" /></template>
