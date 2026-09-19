<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/e/ew3888kre.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":80,"height":80};
const content = `<path class="ew3888kre"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="glyphs:cloud" /></template>
