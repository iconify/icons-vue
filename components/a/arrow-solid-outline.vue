<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/n/nk6pc0bhr.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":80,"height":80};
const content = `<path clip-rule="evenodd" class="nk6pc0bhr"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="glyphs:arrow-solid-outline" /></template>
