<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/e/evtnbubdj.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":48,"height":48};
const content = `<path clip-rule="evenodd" class="evtnbubdj"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="streamline-plump:discount-percent-cutout-remix" /></template>
