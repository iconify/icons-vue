<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/k/k5wd7w_ff.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":80,"height":80};
const content = `<path clip-rule="evenodd" class="k5wd7w_ff"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="glyphs:glasses-outline" /></template>
