<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/a/a6hb1eb2s.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="a6hb1eb2s primary"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="iconaut:chart-column-big-duotone" /></template>
