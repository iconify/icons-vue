<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/u/upp1jkb8l.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":80,"height":80};
const content = `<path clip-rule="evenodd" class="upp1jkb8l"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="glyphs:battery-3-bold" /></template>
