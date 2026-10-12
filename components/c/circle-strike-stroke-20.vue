<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/c/czkug8blo.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":20,"height":20};
const content = `<path class="czkug8blo"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="garden:circle-strike-stroke-20" /></template>
