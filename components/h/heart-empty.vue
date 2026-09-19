<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/l/lzna4a00y.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":1063,"height":1000};
const content = `<path class="lzna4a00y"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="websymbol:heart-empty" /></template>
