<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/p/poal0b8dc.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":48,"height":48};
const content = `<path clip-rule="evenodd" class="poal0b8dc"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="streamline-plump:dna-remix" /></template>
