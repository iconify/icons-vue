<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/v/vkf55sbnb.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":80,"height":80};
const content = `<path clip-rule="evenodd" class="vkf55sbnb"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="glyphs:laugh-squint-bold" /></template>
