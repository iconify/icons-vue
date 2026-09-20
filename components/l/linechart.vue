<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/h/hhf158btj.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":512,"height":512};
const content = `<path clip-rule="evenodd" class="hhf158btj"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="ix:linechart" /></template>
