<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/l/l84ftsbtd.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":32,"height":32};
const content = `<path class="l84ftsbtd"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="carbon:decision-node" /></template>
