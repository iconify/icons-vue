<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/x/x12zc6b4o.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":80,"height":80};
const content = `<path clip-rule="evenodd" class="x12zc6b4o"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="glyphs:angry-bold" /></template>
