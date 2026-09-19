<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/l/lzebt0ozr.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":80,"height":80};
const content = `<path class="lzebt0ozr"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="glyphs:fog-bold" /></template>
