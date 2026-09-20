<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/a/axu4wiuad.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path clip-rule="evenodd" class="axu4wiuad"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="streamline-sharp:filter-2-remix" /></template>
