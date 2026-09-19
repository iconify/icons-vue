<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/k/kjqkx1pdm.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":80,"height":80};
const content = `<path class="kjqkx1pdm"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="glyphs:circle-half-duo" /></template>
