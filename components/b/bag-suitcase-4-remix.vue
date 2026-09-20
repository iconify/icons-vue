<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/m/mex-ngb_x.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":48,"height":48};
const content = `<path clip-rule="evenodd" class="mex-ngb_x"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="streamline-plump:bag-suitcase-4-remix" /></template>
