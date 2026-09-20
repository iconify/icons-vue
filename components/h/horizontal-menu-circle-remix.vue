<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/n/njf8bp8mn.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":48,"height":48};
const content = `<path clip-rule="evenodd" class="njf8bp8mn"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="streamline-plump:horizontal-menu-circle-remix" /></template>
