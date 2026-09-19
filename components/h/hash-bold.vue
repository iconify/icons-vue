<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/n/njixr5bac.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":80,"height":80};
const content = `<path class="njixr5bac"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="glyphs:hash-bold" /></template>
