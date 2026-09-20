<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/v/vr4f3tbci.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":16,"height":16};
const content = `<path class="vr4f3tbci"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="vaadin:envelope-o" /></template>
