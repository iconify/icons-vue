<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/x/xnph_esxv.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":48,"height":48};
const content = `<path clip-rule="evenodd" class="xnph_esxv"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="streamline-plump:electric-cord-1-remix" /></template>
