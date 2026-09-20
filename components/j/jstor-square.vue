<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/i/i__a2hb_t.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":448,"height":512};
const content = `<path class="i__a2hb_t"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="academicons:jstor-square" /></template>
