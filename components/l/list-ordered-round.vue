<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/r/rdf4o6ifl.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="rdf4o6ifl"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="coolicons:list-ordered-round" /></template>
