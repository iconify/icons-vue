<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/r/r_mm_ifmh.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="r_mm_ifmh"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="bxs:comment-check" /></template>
