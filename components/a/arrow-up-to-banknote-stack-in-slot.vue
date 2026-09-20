<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/e/eqej7pdcn.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":15,"height":15};
const content = `<path class="eqej7pdcn"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="pinhead:arrow-up-to-banknote-stack-in-slot" /></template>
