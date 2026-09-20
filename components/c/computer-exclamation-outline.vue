<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/z/zf42_qb-c.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":16,"height":16};
const content = `<path class="zf42_qb-c"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="lsicon:computer-exclamation-outline" /></template>
