<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/s/szplzeb1y.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":14,"height":14};
const content = `<path clip-rule="evenodd" class="szplzeb1y"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="streamline-flex:champagne-party-alcohol-remix" /></template>
