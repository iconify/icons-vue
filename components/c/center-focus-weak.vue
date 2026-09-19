<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/e/ed4eppq-r.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":80,"height":80};
const content = `<path class="ed4eppq-r"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="glyphs:center-focus-weak" /></template>
