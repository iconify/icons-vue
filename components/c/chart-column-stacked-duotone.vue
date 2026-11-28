<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/e/evq3bovfu.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="evq3bovfu primary"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="iconaut:chart-column-stacked-duotone" /></template>
