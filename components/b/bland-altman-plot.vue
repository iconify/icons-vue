<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/i/i791vdbtc.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":32,"height":32};
const content = `<path class="i791vdbtc"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="carbon:bland-altman-plot" /></template>
