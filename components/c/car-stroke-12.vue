<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/r/rdla-ibad.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":12,"height":12};
const content = `<path class="rdla-ibad"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="garden:car-stroke-12" /></template>
