<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/v/v0flmbb4m.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":1536,"height":1536};
const content = `<g transform="translate(1536 0) scale(-1 1)"><path class="v0flmbb4m"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="fa:arrow-circle-right" /></template>
