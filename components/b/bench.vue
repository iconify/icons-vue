<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/u/uj4jt58kl.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":80,"height":80};
const content = `<path class="uj4jt58kl"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="glyphs:bench" /></template>
