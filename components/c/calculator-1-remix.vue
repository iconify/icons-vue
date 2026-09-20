<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/y/y--xh7bkm.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":48,"height":48};
const content = `<path clip-rule="evenodd" class="y--xh7bkm"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="streamline-plump:calculator-1-remix" /></template>
