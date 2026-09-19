<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/q/qmgfy0_4f.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":80,"height":80};
const content = `<path clip-rule="evenodd" class="qmgfy0_4f"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="glyphs:bell-slash-outline" /></template>
