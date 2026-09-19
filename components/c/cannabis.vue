<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/n/nkspiv3bv.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":80,"height":80};
const content = `<path class="nkspiv3bv"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="glyphs:cannabis" /></template>
