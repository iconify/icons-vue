<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/p/pp3n8fbra.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":80,"height":80};
const content = `<path class="pp3n8fbra"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="glyphs:hand-holding-dollar" /></template>
