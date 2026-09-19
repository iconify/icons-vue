<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/u/usud5lbtc.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":16,"height":16};
const content = `<path clip-rule="evenodd" class="usud5lbtc"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="codicon:layout-density-default" /></template>
