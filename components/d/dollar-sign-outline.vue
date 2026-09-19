<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/o/ojpr01bxm.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":80,"height":80};
const content = `<path class="ojpr01bxm"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="glyphs:dollar-sign-outline" /></template>
