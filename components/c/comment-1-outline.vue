<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/s/s5zgcqb2e.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":80,"height":80};
const content = `<path clip-rule="evenodd" class="s5zgcqb2e"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="glyphs:comment-1-outline" /></template>
