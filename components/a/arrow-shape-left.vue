<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/u/ul6fgxl1d.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":16,"height":16};
const content = `<path clip-rule="evenodd" class="ul6fgxl1d"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="gravity-ui:arrow-shape-left" /></template>
