<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/j/jt0s0kb7p.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":80,"height":80};
const content = `<path clip-rule="evenodd" class="jt0s0kb7p"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="glyphs:layer-group-outline" /></template>
