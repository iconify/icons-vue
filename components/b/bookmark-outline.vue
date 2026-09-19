<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/s/ssmn0jj2v.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":80,"height":80};
const content = `<path clip-rule="evenodd" class="ssmn0jj2v"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="glyphs:bookmark-outline" /></template>
