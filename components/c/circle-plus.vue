<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/p/prhe_ibqx.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":17,"height":16};
const content = `<path class="prhe_ibqx"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="si-glyph:circle-plus" /></template>
