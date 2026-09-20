<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/i/i-q11zbzb.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="i-q11zbzb"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="lucide:bitcoin" /></template>
