<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/g/gpfi1cbcb.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="gpfi1cbcb"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="keyline-icons:chart-line-up-sharp-fill" /></template>
