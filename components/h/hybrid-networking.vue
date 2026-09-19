<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/c/c2yv4rdoa.css';
import '../../css/u/uyf_mbp3e.css';
import '../../css/w/w5qbufbiq.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":32,"height":32};
const content = `<path class="c2yv4rdoa"/><path class="uyf_mbp3e"/><path class="w5qbufbiq"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="carbon:hybrid-networking" /></template>
