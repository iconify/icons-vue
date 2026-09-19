<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/l/lldg-yb_z.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":32,"height":32};
const content = `<path class="lldg-yb_z"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="fluent-emoji-high-contrast:flexed-biceps" /></template>
