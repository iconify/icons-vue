<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/f/f0kbp0bsn.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":80,"height":80};
const content = `<path class="f0kbp0bsn"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="glyphs:grid-remove" /></template>
