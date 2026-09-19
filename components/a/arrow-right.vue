<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/t/ts_mtbbcn.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":17,"height":16};
const content = `<path class="ts_mtbbcn"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="si-glyph:arrow-right" /></template>
