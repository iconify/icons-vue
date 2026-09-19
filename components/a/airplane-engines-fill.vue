<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/z/z80-l5b-j.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":16,"height":16};
const content = `<path class="z80-l5b-j"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="bi:airplane-engines-fill" /></template>
