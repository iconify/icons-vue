<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/f/fhitcdc0n.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":80,"height":80};
const content = `<path clip-rule="evenodd" class="fhitcdc0n"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="glyphs:heartbreak-bold" /></template>
