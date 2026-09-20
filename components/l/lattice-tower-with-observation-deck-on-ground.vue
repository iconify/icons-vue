<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/c/ctfz9yp6p.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":15,"height":15};
const content = `<path class="ctfz9yp6p"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="pinhead:lattice-tower-with-observation-deck-on-ground" /></template>
