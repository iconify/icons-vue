<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/f/fb2-eywbz.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":80,"height":80};
const content = `<path class="fb2-eywbz"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="glyphs:ampersand" /></template>
