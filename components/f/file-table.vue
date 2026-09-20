<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/o/oe3oz-bur.css';
import '../../css/d/djgo8gpso.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":16,"height":16};
const content = `<path class="oe3oz-bur"/><path class="djgo8gpso"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="vaadin:file-table" /></template>
