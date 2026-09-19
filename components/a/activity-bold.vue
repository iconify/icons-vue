<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/s/s__ilhbph.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":80,"height":80};
const content = `<path class="s__ilhbph"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="glyphs:activity-bold" /></template>
