<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/p/p_fay6bwq.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":2048,"height":2048};
const content = `<path class="p_fay6bwq"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="fluent-mdl2:arrow-down-right-mirrored-8" /></template>
