<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/w/w-000_rgo.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":14,"height":14};
const content = `<path class="w-000_rgo"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="streamline-flex:computer-chip-1" /></template>
