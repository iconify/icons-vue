<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/n/nhcm4hbxh.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":80,"height":80};
const content = `<path clip-rule="evenodd" class="nhcm4hbxh"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="glyphs:globe-outline" /></template>
