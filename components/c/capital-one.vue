<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/f/f0yul3-vt.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":512,"height":512};
const content = `<path class="f0yul3-vt"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="selfhst:capital-one" /></template>
