<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/r/r4oscvhds.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":48,"height":48};
const content = `<path clip-rule="evenodd" class="r4oscvhds"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="healthicons:alcohol-cessation" /></template>
