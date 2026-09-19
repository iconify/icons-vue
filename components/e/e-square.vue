<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/i/i8mm0wtyn.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":1792,"height":1792};
const content = `<path class="i8mm0wtyn"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="vs:e-square" /></template>
