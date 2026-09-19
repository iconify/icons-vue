<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/o/or2sbebws.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":80,"height":80};
const content = `<path class="or2sbebws"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="glyphs:i-outline" /></template>
