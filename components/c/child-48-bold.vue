<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/h/hj1-uqbic.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":48,"height":48};
const content = `<path class="hj1-uqbic"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="energy-icons:child-48-bold" /></template>
