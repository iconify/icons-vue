<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/h/hjfwlht7x.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":17,"height":16};
const content = `<path class="hjfwlht7x"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="si-glyph:clover" /></template>
