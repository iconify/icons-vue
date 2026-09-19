<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/g/gpbomdi0w.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":80,"height":80};
const content = `<path clip-rule="evenodd" class="gpbomdi0w"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="glyphs:comment-exclamation-bold" /></template>
