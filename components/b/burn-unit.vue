<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/o/osd--hbtk.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":48,"height":48};
const content = `<path clip-rule="evenodd" class="osd--hbtk"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="healthicons:burn-unit" /></template>
