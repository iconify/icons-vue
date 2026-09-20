<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/q/qbxsy4b3a.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":16,"height":16};
const content = `<path class="qbxsy4b3a"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="roentgen:bottle-and-wine-glass" /></template>
