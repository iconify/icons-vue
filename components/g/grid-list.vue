<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/e/ev5qcabkn.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":80,"height":80};
const content = `<path class="ev5qcabkn"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="glyphs:grid-list" /></template>
