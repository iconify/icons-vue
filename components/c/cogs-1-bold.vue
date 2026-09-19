<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/j/j_rjcdbjn.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":90,"height":80};
const content = `<path clip-rule="evenodd" class="j_rjcdbjn"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="glyphs:cogs-1-bold" /></template>
