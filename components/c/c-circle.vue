<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/r/rkl_jct_l.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":16,"height":16};
const content = `<path class="rkl_jct_l"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="bi:c-circle" /></template>
