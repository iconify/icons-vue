<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/j/jqipt_dmz.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":80,"height":80};
const content = `<path clip-rule="evenodd" class="jqipt_dmz"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="glyphs:frown-open-bold" /></template>
