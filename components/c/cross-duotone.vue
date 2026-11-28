<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/f/fele_wbis.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="fele_wbis primary"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="iconaut:cross-duotone" /></template>
