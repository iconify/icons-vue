<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/u/u2e5mzbrb.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="u2e5mzbrb"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="gridicons:crop" /></template>
