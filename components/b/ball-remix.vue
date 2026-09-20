<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/s/sig5-f5ft.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":48,"height":48};
const content = `<path clip-rule="evenodd" class="sig5-f5ft"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="streamline-plump:ball-remix" /></template>
