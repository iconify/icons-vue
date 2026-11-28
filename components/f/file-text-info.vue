<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/a/axul6db8p.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="axul6db8p"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="noviair-light:file-text-info" /></template>
