<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/j/jsessgr_y.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":80,"height":80};
const content = `<path clip-rule="evenodd" class="jsessgr_y"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="glyphs:loveseat-outline" /></template>
