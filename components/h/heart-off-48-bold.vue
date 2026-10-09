<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/y/y-kb2o5pg.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":48,"height":48};
const content = `<path class="y-kb2o5pg"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="energy-icons:heart-off-48-bold" /></template>
