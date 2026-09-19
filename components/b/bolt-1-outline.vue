<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/a/athg_qphj.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":80,"height":80};
const content = `<path clip-rule="evenodd" class="athg_qphj"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="glyphs:bolt-1-outline" /></template>
