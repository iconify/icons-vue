<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/n/nb7v0vb6e.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":80,"height":80};
const content = `<path clip-rule="evenodd" class="nb7v0vb6e"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="glyphs:bezier-square-outline" /></template>
