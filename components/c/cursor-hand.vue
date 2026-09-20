<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/r/rdfurtb_t.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":32,"height":32};
const content = `<path class="rdfurtb_t"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="streamline-pixel:cursor-hand" /></template>
