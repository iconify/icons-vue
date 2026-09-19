<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/f/fhxqb1l5k.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":12,"height":12};
const content = `<path class="fhxqb1l5k"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="codicon:circle-small-filled-compact" /></template>
