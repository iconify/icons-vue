<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/n/n1mxsq6ro.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":80,"height":80};
const content = `<path clip-rule="evenodd" class="n1mxsq6ro"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="glyphs:laugh-beam-bold" /></template>
