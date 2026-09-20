<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/s/swaa762og.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":48,"height":48};
const content = `<path clip-rule="evenodd" class="swaa762og"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="streamline-plump:global-warming-2-solid" /></template>
