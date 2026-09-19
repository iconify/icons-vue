<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/g/g-7-8jbgk.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":80,"height":80};
const content = `<path class="g-7-8jbgk"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="glyphs:arrow-solid-curve" /></template>
