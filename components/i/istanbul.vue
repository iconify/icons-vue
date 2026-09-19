<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/q/qb41g0omf.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":512,"height":512};
const content = `<path class="qb41g0omf"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="file-icons:istanbul" /></template>
