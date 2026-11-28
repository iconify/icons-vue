<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/m/m9oeji4xy.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="m9oeji4xy"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="noviair:flag-finish-check" /></template>
