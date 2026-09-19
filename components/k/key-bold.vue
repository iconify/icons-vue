<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/n/nh68cdc1l.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":80,"height":80};
const content = `<path clip-rule="evenodd" class="nh68cdc1l"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="glyphs:key-bold" /></template>
