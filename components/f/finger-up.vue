<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/j/jfs7habgj.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":17,"height":16};
const content = `<path class="jfs7habgj"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="si-glyph:finger-up" /></template>
