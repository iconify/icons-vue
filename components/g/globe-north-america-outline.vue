<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/z/z2-pfdccx.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":80,"height":80};
const content = `<path clip-rule="evenodd" class="z2-pfdccx"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="glyphs:globe-north-america-outline" /></template>
