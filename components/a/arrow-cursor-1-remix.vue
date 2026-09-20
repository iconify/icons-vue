<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/n/nkusribsk.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":48,"height":48};
const content = `<path clip-rule="evenodd" class="nkusribsk"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="streamline-plump:arrow-cursor-1-remix" /></template>
