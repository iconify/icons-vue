<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/n/ne3sn9etj.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":80,"height":80};
const content = `<path clip-rule="evenodd" class="ne3sn9etj"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="glyphs:exclude-outline" /></template>
