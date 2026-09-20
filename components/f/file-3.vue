<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/r/r541g87yf.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":512,"height":512};
const content = `<path class="r541g87yf"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="subway:file-3" /></template>
