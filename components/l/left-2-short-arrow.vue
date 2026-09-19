<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/i/iv2q-whaf.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="iv2q-whaf"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="guidance:left-2-short-arrow" /></template>
