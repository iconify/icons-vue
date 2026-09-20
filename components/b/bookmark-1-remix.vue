<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/u/uemcgcccl.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":48,"height":48};
const content = `<path clip-rule="evenodd" class="uemcgcccl"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="streamline-plump:bookmark-1-remix" /></template>
