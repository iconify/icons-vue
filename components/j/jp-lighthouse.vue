<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/i/i7-vrkbsh.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":15,"height":15};
const content = `<path class="i7-vrkbsh"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="pinhead:jp-lighthouse" /></template>
