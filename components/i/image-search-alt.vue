<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/e/ev-_rkitm.css';
import '../../css/l/lxavlrbta.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":32,"height":32};
const content = `<path class="ev-_rkitm"/><path class="lxavlrbta"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="carbon:image-search-alt" /></template>
