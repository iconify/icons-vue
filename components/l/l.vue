<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/n/nfylp182e.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":80,"height":80};
const content = `<path class="nfylp182e"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="glyphs:l" /></template>
