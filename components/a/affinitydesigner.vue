<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/e/e0srfgb4g.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":512,"height":512};
const content = `<path class="e0srfgb4g"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="file-icons:affinitydesigner" /></template>
