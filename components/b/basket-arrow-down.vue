<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/z/zzlp1fnmj.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":16,"height":16};
const content = `<path class="zzlp1fnmj"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="si-glyph:basket-arrow-down" /></template>
