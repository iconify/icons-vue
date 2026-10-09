<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/p/p0bcohnco.css';
import '../../css/y/yvipk86za.css';
import '../../css/v/vekg20bug.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":48,"height":48};
const content = `<path class="p0bcohnco"/><path class="yvipk86za"/><path class="vekg20bug"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="energy-icons:git-pull-request-48-bold" /></template>
