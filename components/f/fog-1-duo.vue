<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/s/snt-orb5x.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":80,"height":80};
const content = `<path class="snt-orb5x"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="glyphs:fog-1-duo" /></template>
