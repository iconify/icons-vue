<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/j/jqb2u5bqj.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":80,"height":80};
const content = `<path clip-rule="evenodd" class="jqb2u5bqj"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="glyphs:clipboard-outline" /></template>
