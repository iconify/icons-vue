<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/u/ugioa106r.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":80,"height":80};
const content = `<path class="ugioa106r"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="glyphs:hand-fist" /></template>
