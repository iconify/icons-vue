<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/a/a9y4ge1vr.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":80,"height":80};
const content = `<path clip-rule="evenodd" class="a9y4ge1vr"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="glyphs:battery-bolt-bold" /></template>
