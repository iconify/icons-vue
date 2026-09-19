<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/z/z8bxqwb9n.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":80,"height":80};
const content = `<path class="z8bxqwb9n"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="glyphs:b-duo" /></template>
