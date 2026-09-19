<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/q/qswxg_blr.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":80,"height":80};
const content = `<path class="qswxg_blr"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="glyphs:d-duo" /></template>
