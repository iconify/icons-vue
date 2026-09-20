<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/u/uxo32nbik.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":512,"height":512};
const content = `<path clip-rule="evenodd" class="uxo32nbik"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="ix:chart-types-filled" /></template>
