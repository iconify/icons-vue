<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/v/v-seggbcn.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":48,"height":48};
const content = `<path clip-rule="evenodd" class="v-seggbcn"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="streamline-plump:graph-dot-remix" /></template>
