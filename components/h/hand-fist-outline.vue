<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/h/hg33djbet.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":80,"height":80};
const content = `<path clip-rule="evenodd" class="hg33djbet"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="glyphs:hand-fist-outline" /></template>
