<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/l/l4ix4_bwv.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":32,"height":32};
const content = `<path class="l4ix4_bwv"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="fluent-emoji-high-contrast:custard" /></template>
