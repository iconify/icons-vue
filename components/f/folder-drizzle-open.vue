<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/p/pffnfbbjn.css';
import '../../css/n/nr5mntn4t.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":16,"height":16};
const content = `<path class="pffnfbbjn"/><path class="nr5mntn4t"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="material-icon-theme:folder-drizzle-open" /></template>
