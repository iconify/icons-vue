<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/o/o9etvphaj.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="o9etvphaj"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="noviair-light:frying-pan" /></template>
