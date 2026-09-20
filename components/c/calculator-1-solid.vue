<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/s/s9rrn-bjw.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":48,"height":48};
const content = `<path clip-rule="evenodd" class="s9rrn-bjw"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="streamline-plump:calculator-1-solid" /></template>
