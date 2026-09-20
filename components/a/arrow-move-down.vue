<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/u/u6ia8cbgb.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="u6ia8cbgb"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="tabler:arrow-move-down" /></template>
