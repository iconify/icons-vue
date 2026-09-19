<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/x/xlj_ihbrk.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":512,"height":512};
const content = `<path class="xlj_ihbrk"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="ps:guy-sad" /></template>
