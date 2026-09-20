<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/q/q8thah3mt.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":16,"height":16};
const content = `<path class="q8thah3mt"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="oui:continuity-above" /></template>
