<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/f/ff_0uo-vb.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":80,"height":80};
const content = `<path clip-rule="evenodd" class="ff_0uo-vb"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="glyphs:hand-horns-outline" /></template>
