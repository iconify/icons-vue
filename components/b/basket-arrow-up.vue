<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/i/ic_j8siyi.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":16,"height":16};
const content = `<path class="ic_j8siyi"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="si-glyph:basket-arrow-up" /></template>
