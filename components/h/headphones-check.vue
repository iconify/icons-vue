<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/r/rdfvp4bom.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="rdfvp4bom"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="noviair:headphones-check" /></template>
