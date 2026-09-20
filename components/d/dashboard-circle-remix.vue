<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/q/qbdn16phg.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":14,"height":14};
const content = `<path clip-rule="evenodd" class="qbdn16phg"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="streamline:dashboard-circle-remix" /></template>
