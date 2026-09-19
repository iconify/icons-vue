<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/t/t3oe6jemu.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":80,"height":80};
const content = `<path class="t3oe6jemu"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="glyphs:arrow-solid-line-end" /></template>
