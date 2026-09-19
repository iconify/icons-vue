<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/d/dblk24e3g.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":2048,"height":2048};
const content = `<path class="dblk24e3g"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="fluent-mdl2:circle-shape-solid" /></template>
