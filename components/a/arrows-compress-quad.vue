<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/c/cdlztobds.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":80,"height":80};
const content = `<path class="cdlztobds"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="glyphs:arrows-compress-quad" /></template>
