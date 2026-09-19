<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/l/lggnhgbti.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":80,"height":80};
const content = `<path clip-rule="evenodd" class="lggnhgbti"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="glyphs:bezier-curve-outline" /></template>
