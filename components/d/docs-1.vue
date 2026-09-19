<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/p/pykjl9apf.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":80,"height":80};
const content = `<path class="pykjl9apf"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="glyphs:docs-1" /></template>
