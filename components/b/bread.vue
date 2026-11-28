<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/n/nz7ctgbrf.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="nz7ctgbrf"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="noviair-light:bread" /></template>
