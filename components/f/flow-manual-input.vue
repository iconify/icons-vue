<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/l/ltl30k2-b.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="ltl30k2-b"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="iconaut:flow-manual-input" /></template>
