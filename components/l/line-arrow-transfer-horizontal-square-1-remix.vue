<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/w/waibshbfh.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":48,"height":48};
const content = `<path clip-rule="evenodd" class="waibshbfh"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="streamline-plump:line-arrow-transfer-horizontal-square-1-remix" /></template>
