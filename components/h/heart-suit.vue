<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/u/uroqbab3z.css';
import '../../css/d/d23743b9c.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":72,"height":72};
const content = `<path class="uroqbab3z"/><path class="d23743b9c"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="openmoji:heart-suit" /></template>
