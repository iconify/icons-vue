<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/e/ea-d-nbfx.css';
import '../../css/j/jjn413bew.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":20,"height":20};
const content = `<path class="ea-d-nbfx"/><path class="jjn413bew"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="energy-icons:jersey-20-bold" /></template>
