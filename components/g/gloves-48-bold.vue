<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/p/p7de_1bdc.css';
import '../../css/d/djawiyg4a.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":48,"height":48};
const content = `<path class="p7de_1bdc"/><path class="djawiyg4a"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="energy-icons:gloves-48-bold" /></template>
