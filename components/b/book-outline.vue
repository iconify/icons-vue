<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/r/r5ko7v8oa.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":80,"height":80};
const content = `<path clip-rule="evenodd" class="r5ko7v8oa"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="glyphs:book-outline" /></template>
