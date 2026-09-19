<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/h/hj-lhxb-v.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":17,"height":16};
const content = `<path class="hj-lhxb-v"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="si-glyph:bikini" /></template>
