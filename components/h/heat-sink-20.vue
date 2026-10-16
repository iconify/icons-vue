<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/c/ci9il8bto.css';
import '../../css/n/np35iacps.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":20,"height":20};
const content = `<path class="ci9il8bto"/><path class="np35iacps"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="energy-icons:heat-sink-20" /></template>
