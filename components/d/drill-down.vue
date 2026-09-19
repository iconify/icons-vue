<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/k/k1p_xpb1s.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":2048,"height":2048};
const content = `<path class="k1p_xpb1s"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="fluent-mdl2:drill-down" /></template>
