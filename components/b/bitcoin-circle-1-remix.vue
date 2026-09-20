<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/b/bm58ocm0p.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":48,"height":48};
const content = `<path clip-rule="evenodd" class="bm58ocm0p"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="streamline-plump:bitcoin-circle-1-remix" /></template>
