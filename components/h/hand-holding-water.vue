<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/d/d1n06kb2c.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":80,"height":80};
const content = `<path class="d1n06kb2c"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="glyphs:hand-holding-water" /></template>
