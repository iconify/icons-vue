<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/k/kh-gn6b-g.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":80,"height":80};
const content = `<path clip-rule="evenodd" class="kh-gn6b-g"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="glyphs-poly:hand-horns" /></template>
