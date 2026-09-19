<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/u/uvkc56lvw.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":80,"height":80};
const content = `<path clip-rule="evenodd" class="uvkc56lvw"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="glyphs:grid-sm-outline" /></template>
