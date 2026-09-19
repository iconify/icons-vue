<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/z/zm9rcacmh.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":17,"height":16};
const content = `<path class="zm9rcacmh"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="si-glyph:arrow-change" /></template>
