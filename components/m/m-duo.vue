<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/s/s9_3scbjc.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":80,"height":80};
const content = `<path class="s9_3scbjc"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="glyphs:m-duo" /></template>
