<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/i/ijsei2bsi.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":80,"height":80};
const content = `<path class="ijsei2bsi"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="glyphs:bezier-triangle" /></template>
