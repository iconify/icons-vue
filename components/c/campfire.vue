<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/f/fyv35uw7m.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":80,"height":80};
const content = `<path class="fyv35uw7m"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="glyphs:campfire" /></template>
