<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/e/e6_ehmbhe.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":48,"height":48};
const content = `<path clip-rule="evenodd" class="e6_ehmbhe"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="healthicons:human-resoruces" /></template>
