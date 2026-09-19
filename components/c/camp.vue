<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/k/kgvzk42-j.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":80,"height":80};
const content = `<path class="kgvzk42-j"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="glyphs:camp" /></template>
