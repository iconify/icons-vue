<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/m/mj_9ii32x.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":48,"height":48};
const content = `<path clip-rule="evenodd" class="mj_9ii32x"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="streamline-plump:align-selection-remix" /></template>
