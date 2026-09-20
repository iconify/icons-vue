<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/f/fw2yh03_d.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="fw2yh03_d"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="keyline-icons:chart-tree-map" /></template>
