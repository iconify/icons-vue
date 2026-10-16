<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/u/uxvnz_b5x.css';
import '../../css/t/ty8mqjb4w.css';
import '../../css/p/p-x0sqbzb.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":48,"height":48};
const content = `<path class="uxvnz_b5x"/><path class="ty8mqjb4w"/><path class="p-x0sqbzb"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="energy-icons:house-hydrogen-48-bold" /></template>
