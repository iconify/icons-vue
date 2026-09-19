<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/c/cwb9frtjj.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":80,"height":80};
const content = `<path class="cwb9frtjj"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="glyphs:align-justify" /></template>
