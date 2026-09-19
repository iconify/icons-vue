<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/n/nl834o1cg.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":48,"height":48};
const content = `<path clip-rule="evenodd" class="nl834o1cg"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="healthicons:chlamydia" /></template>
