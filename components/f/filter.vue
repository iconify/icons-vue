<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/i/irbofw-4i.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":16,"height":16};
const content = `<path class="irbofw-4i"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="oui:filter" /></template>
