<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/c/cn0srzhrc.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="cn0srzhrc"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="hugeicons:cursor-circle-selection-01" /></template>
