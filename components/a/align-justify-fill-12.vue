<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/g/gfg3w-tef.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":12,"height":12};
const content = `<path class="gfg3w-tef"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="garden:align-justify-fill-12" /></template>
