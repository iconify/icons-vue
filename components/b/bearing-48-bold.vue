<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/e/e_6rndbde.css';
import '../../css/t/tem3d3bqw.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":48,"height":48};
const content = `<path class="e_6rndbde"/><path class="tem3d3bqw"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="energy-icons:bearing-48-bold" /></template>
