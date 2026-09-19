<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/x/xe88eacqk.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":80,"height":80};
const content = `<path class="xe88eacqk"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="glyphs:cli-duo" /></template>
