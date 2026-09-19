<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/h/h2wu78b0j.css';
import '../../css/n/nr_by2_hg.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="h2wu78b0j"/><path class="nr_by2_hg"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="bx:bx-zoom-out" /></template>
