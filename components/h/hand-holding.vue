<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/o/ohrg4zbtv.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":80,"height":80};
const content = `<path clip-rule="evenodd" class="ohrg4zbtv"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="glyphs-poly:hand-holding" /></template>
