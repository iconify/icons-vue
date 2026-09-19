<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/c/cqgee5byp.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":80,"height":80};
const content = `<path clip-rule="evenodd" class="cqgee5byp"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="glyphs:building-1-bold" /></template>
