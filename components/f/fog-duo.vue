<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/l/l6mhqvx1u.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":80,"height":80};
const content = `<path class="l6mhqvx1u"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="glyphs:fog-duo" /></template>
