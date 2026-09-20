<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/d/dg1szrr6a.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":48,"height":48};
const content = `<path clip-rule="evenodd" class="dg1szrr6a"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="streamline-plump:file-report-remix" /></template>
