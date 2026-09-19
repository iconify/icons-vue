<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/e/ewfjegb_z.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":80,"height":80};
const content = `<path class="ewfjegb_z"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="glyphs:ampersand-1-bold" /></template>
