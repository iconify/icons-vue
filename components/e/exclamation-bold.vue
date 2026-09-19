<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/m/m9y09mbbe.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":80,"height":80};
const content = `<path class="m9y09mbbe"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="glyphs:exclamation-bold" /></template>
