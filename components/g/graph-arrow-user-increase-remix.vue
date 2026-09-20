<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/x/xyp0m5ztu.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":48,"height":48};
const content = `<path clip-rule="evenodd" class="xyp0m5ztu"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="streamline-plump:graph-arrow-user-increase-remix" /></template>
