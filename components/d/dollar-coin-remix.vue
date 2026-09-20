<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/n/nv-za9b3j.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":48,"height":48};
const content = `<path clip-rule="evenodd" class="nv-za9b3j"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="streamline-plump:dollar-coin-remix" /></template>
