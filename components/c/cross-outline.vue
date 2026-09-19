<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/o/okmoa9bvv.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":80,"height":80};
const content = `<path clip-rule="evenodd" class="okmoa9bvv"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="glyphs:cross-outline" /></template>
