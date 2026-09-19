<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/r/r9pe_nrcw.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":84,"height":80};
const content = `<path clip-rule="evenodd" class="r9pe_nrcw"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="glyphs:cogs-bold" /></template>
