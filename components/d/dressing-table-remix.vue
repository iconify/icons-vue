<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/l/llrxv2dez.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":14,"height":14};
const content = `<path clip-rule="evenodd" class="llrxv2dez"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="streamline:dressing-table-remix" /></template>
