<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/t/tzh-aib4t.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":512,"height":512};
const content = `<path class="tzh-aib4t"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="game-icons:laptop" /></template>
