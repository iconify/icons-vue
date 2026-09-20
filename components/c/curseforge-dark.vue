<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/i/iwj6fiudg.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":260,"height":256};
const content = `<path class="iwj6fiudg"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="thesvg-color:curseforge-dark" /></template>
