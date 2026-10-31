<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/e/e2gvucboh.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":15,"height":15};
const content = `<path class="e2gvucboh"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="pinhead:eaved-open-gabled-building-with-chimney-and-window" /></template>
