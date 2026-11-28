<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/g/gjfo7acdd.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="gjfo7acdd primary"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="iconaut:chart-network-duotone" /></template>
