<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/s/sfhcnobsq.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":80,"height":80};
const content = `<path class="sfhcnobsq"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="glyphs:h-bold" /></template>
