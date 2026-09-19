<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/p/pf9onqh5v.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":80,"height":80};
const content = `<path class="pf9onqh5v"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="glyphs:ampersand-duo" /></template>
