<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/f/f7c4ygb3u.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":80,"height":80};
const content = `<path class="f7c4ygb3u"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="glyphs:docs-bold" /></template>
