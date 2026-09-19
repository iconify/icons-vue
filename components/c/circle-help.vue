<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/p/p2sfrl00p.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":17,"height":16};
const content = `<path class="p2sfrl00p"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="si-glyph:circle-help" /></template>
