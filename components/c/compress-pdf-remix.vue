<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/h/hp4u6spcg.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":48,"height":48};
const content = `<path clip-rule="evenodd" class="hp4u6spcg"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="streamline-plump:compress-pdf-remix" /></template>
