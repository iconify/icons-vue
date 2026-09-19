<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/u/uk-3pyb8k.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":80,"height":80};
const content = `<path class="uk-3pyb8k"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="glyphs:badge-duo" /></template>
