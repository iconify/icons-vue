<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/q/q16dfk8ej.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":256,"height":256};
const content = `<path class="q16dfk8ej"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="pullo:caret-down-up-thin" /></template>
