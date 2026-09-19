<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/b/bp2s7bc1i.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":80,"height":80};
const content = `<path class="bp2s7bc1i"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="glyphs:bars-offset-1" /></template>
