<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/y/yglz00bkg.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":80,"height":80};
const content = `<path class="yglz00bkg"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="glyphs:eject" /></template>
