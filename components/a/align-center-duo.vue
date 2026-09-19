<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/a/aplqkl7uk.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":80,"height":80};
const content = `<path class="aplqkl7uk"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="glyphs:align-center-duo" /></template>
