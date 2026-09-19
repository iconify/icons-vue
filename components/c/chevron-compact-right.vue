<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/m/msmt2ql3o.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":16,"height":16};
const content = `<path class="msmt2ql3o"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="bi:chevron-compact-right" /></template>
