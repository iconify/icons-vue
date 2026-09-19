<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/a/ac78ep3-o.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":80,"height":80};
const content = `<path clip-rule="evenodd" class="ac78ep3-o"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="glyphs:bezier-hexagon-outline" /></template>
