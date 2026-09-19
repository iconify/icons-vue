<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/d/dkwkeiw1k.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":80,"height":80};
const content = `<path class="dkwkeiw1k"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="glyphs:l-outline" /></template>
