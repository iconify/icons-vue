<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/g/g4y2z7h4a.css';
import '../../css/a/akcuay_-h.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":72,"height":72};
const content = `<path class="g4y2z7h4a"/><path class="akcuay_-h"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="openmoji:cloud" /></template>
