<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/r/rgi2qnb5y.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":17,"height":16};
const content = `<path class="rgi2qnb5y"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="si-glyph:link-3" /></template>
