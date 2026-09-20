<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/a/anko6fl-p.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":48,"height":48};
const content = `<path clip-rule="evenodd" class="anko6fl-p"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="streamline-plump:crop-selection-solid" /></template>
