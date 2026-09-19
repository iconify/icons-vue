<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/k/kgyg9pbos.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":32,"height":32};
const content = `<path class="kgyg9pbos"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="carbon:hexagon-vertical-solid" /></template>
