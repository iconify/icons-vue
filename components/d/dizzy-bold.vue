<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/u/u98ht8bdk.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":80,"height":80};
const content = `<path clip-rule="evenodd" class="u98ht8bdk"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="glyphs:dizzy-bold" /></template>
