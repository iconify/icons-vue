<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/c/cfm2d7bww.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":80,"height":80};
const content = `<path class="cfm2d7bww"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="glyphs:activity" /></template>
