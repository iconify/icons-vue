<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/r/rp9z2uxhq.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":256,"height":256};
const content = `<path class="rp9z2uxhq"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="fad:digital0" /></template>
