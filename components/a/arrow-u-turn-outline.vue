<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/g/g5qqi8poj.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":80,"height":80};
const content = `<path clip-rule="evenodd" class="g5qqi8poj"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="glyphs:arrow-u-turn-outline" /></template>
