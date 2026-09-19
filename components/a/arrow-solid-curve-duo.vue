<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/p/pr4wmez8s.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":80,"height":80};
const content = `<path class="pr4wmez8s"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="glyphs:arrow-solid-curve-duo" /></template>
