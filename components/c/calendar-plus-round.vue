<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/r/rkqmcxo3p.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="rkqmcxo3p"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="coolicons:calendar-plus-round" /></template>
