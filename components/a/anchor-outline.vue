<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/f/fxp6_5wni.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":80,"height":80};
const content = `<path clip-rule="evenodd" class="fxp6_5wni"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="glyphs:anchor-outline" /></template>
